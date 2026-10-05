<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="we6xbib7a"/><path class="r53acpbtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:homes-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r53acpbtt {
  d: path("M7 21L7 13.4473L14 8L21 13.4473L21 21ZM3 15L3 14L3 6.8909L8 3L10.956 5.3003L11.3419 5.6006M12 21L12 16L16 16L16 21");
}

.we6xbib7a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.3857 7.2108C13.7469 6.92973 14.2531 6.92973 14.6143 7.2108L21.6143 12.6581C21.8576 12.8475 22 13.1387 22 13.4471V20.9999C21.9999 21.5521 21.5522 21.9999 21 21.9999H7C6.44776 21.9999 6.00007 21.5521 6 20.9999V13.4471C6.00001 13.1387 6.1424 12.8475 6.38574 12.6581L13.3857 7.2108Z");
  stroke: none;
}

</style>
