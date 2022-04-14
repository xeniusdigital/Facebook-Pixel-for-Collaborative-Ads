# Facebook-Pixel-for-Collaborative-Ads
Facebook Pixel for Collaborative Ads

fbq('track', 'ViewContent', {
  contents: [
    { id: 'SKU-1', quantity: 1 }
  ],
  content_type: 'product',
  value: 50,
  currency: 'USD',
})

Or, with minimal parameters:

fbq('track', 'ViewContent', {
  content_ids: ['SKU-1'],
  content_type: 'product',
})


#AddToCartEvent
fbq('track', 'AddToCart', {
  contents: [
    { id: 'SKU-1', quantity: 2 }
  ],
  content_type: 'product',
  value: 100,
  currency: 'USD',
})

#PurchaseEvent
fbq('track', 'Purchase', {
  contents: [
    { id: 'SKU-1', quantity: 2 },
    { id: 'SKU-2', quantity: 1 },
  ],
  content_type: 'product',
  value: 130,
  currency: 'USD',
})



