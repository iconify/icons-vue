<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jwvedsvir"/><path class="sqy-cgo_l"/><path class="g6m793csp"/><path class="d0hlz7c2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bonfire-broken" /></template>
<style>
.d0hlz7c2c {
  d: path("M6 8.86038C6 13.7721 9.73333 15 11.6 15C12.5558 15 13.9398 14.7535 15.1765 14.0397M17.0969 12.2372C17.6485 11.3763 18 10.2701 18 8.86038C18 5.73366 15.999 3.5006 14.1898 2.22031C13.3721 1.64162 12.3529 2.27717 12.3529 3.26468V3.48822C12.3529 4.48412 11.925 6.30196 10.736 7.05807C10.1289 7.4441 9.47331 6.86632 9.39953 6.16158L9.33895 5.58289C9.26852 4.91013 8.56829 4.50173 8.01879 4.9119C7.54443 5.26599 7.05981 5.74788 6.68431 6.36616");
}

.g6m793csp {
  d: path("M15 10C14.8 10.6667 13.92 12 12 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwvedsvir {
  d: path("M20 15L4 22");
}

.sqy-cgo_l {
  d: path("M4 15L9 17.1875M14.5 19.5938L20 22");
}

</style>
