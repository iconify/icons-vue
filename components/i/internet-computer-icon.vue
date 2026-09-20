<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":242};
const content = `<defs><linearGradient id="SVGA4aH3Z3k" x1="26.265%" x2="92.196%" y1="24.011%" y2="77.66%"><stop offset="21%" class="qqgg9d-sr"/><stop offset="68.41%" class="uipw48vus"/></linearGradient><linearGradient id="SVGDlALkbhf" x1="73.735%" x2="7.804%" y1="76.013%" y2="22.341%"><stop offset="21%" class="hl8kuhdwx"/><stop offset="89.29%" class="na3vff9tp"/></linearGradient></defs><path fill="url(#SVGA4aH3Z3k)" class="q9ymykbwl"/><path fill="url(#SVGDlALkbhf)" class="xpr159b1p"/><path class="wio0h_o7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:internet-computer-icon" /></template>
<style>
.hl8kuhdwx {
  stop-color: var(--svg-color--ed1e79, #ed1e79);
}

.na3vff9tp {
  stop-color: var(--svg-color--522785, #522785);
}

.q9ymykbwl {
  d: path("M387.644 0c-28.621 0-59.822 14.667-92.8 43.555c-15.644 13.69-29.156 28.356-39.287 40.09l.089.088v-.089s15.998 17.423 33.688 36.09c9.511-11.29 23.2-26.667 38.932-40.534c29.335-25.689 48.444-31.111 59.378-31.111c41.157 0 74.579 32.622 74.579 72.711c0 39.822-33.51 72.444-74.579 72.711c-1.867 0-4.267-.267-7.29-.889c12.001 5.156 24.89 8.89 37.158 8.89c75.376 0 90.132-49.156 91.11-52.712c2.222-8.978 3.378-18.4 3.378-28.089C512 54.222 456.178 0 387.644 0");
}

.qqgg9d-sr {
  stop-color: var(--svg-color--f15a24, #f15a24);
}

.uipw48vus {
  stop-color: var(--svg-color--fbb03b, #fbb03b);
}

.wio0h_o7s {
  fill: var(--svg-color--29abe2, #29abe2);
  d: path("M417.334 200.444c-38.58-.977-78.667-31.377-86.846-38.933c-21.154-19.555-69.956-72.444-73.776-76.622C220.978 44.8 172.533 0 124.356 0h-.178C65.689.267 16.534 39.911 3.378 92.8c.978-3.467 20.267-53.6 91.022-51.822c38.578.978 78.845 31.822 87.111 39.378c21.156 19.555 69.957 72.444 73.779 76.622c35.732 40 84.177 84.8 132.354 84.8h.178c58.489-.266 107.733-39.911 120.8-92.8c-1.067 3.466-20.445 53.155-91.288 51.466");
}

.xpr159b1p {
  d: path("M124.356 241.778c28.622 0 59.822-14.667 92.8-43.556c15.644-13.689 29.156-28.355 39.287-40.088l-.089-.09v.09s-15.998-17.423-33.688-36.09c-9.51 11.29-23.2 26.667-38.933 40.534c-29.333 25.689-48.444 31.11-59.377 31.11c-41.156-.088-74.578-32.71-74.578-72.8c0-39.821 33.51-72.443 74.578-72.71c1.866 0 4.266.267 7.288.889c-12-5.156-24.888-8.89-37.155-8.89c-75.378 0-90.045 49.156-91.111 52.623A117.4 117.4 0 0 0 0 120.89c0 66.667 55.822 120.89 124.356 120.89");
}

</style>
