<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="ni6hhx7ke"/><path class="xloahgb9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:feather-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ni6hhx7ke {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.2495 18.867L3.5017 12.137C3.4976 12.1004 3.4956 12.0635 3.4956 12.0266C3.4956 11.7614 3.601 11.507 3.7885 11.3195L11.2663 3.8416C12.4455 2.6624 14.0448 1.9999 15.7124 1.9999C19.185 1.9999 22.0001 4.815 22.0001 8.2876C22.0001 9.9552 21.3376 11.5545 20.1584 12.7337L12.6805 20.2115C12.493 20.399 12.2386 20.5044 11.9734 20.5044C11.9365 20.5044 11.8996 20.5024 11.863 20.4983L5.133 19.7505C4.6681 19.6988 4.3012 19.3319 4.2495 18.867ZM13.7433 16.3203L15.389 14.6747L11.6808 13.7334L16.7124 8.7018L15.2982 7.2876L10.3238 12.262L9.5057 8.4307L7.8205 10.1159L8.6386 13.9472L6.0075 16.5783L6.1489 17.8511L7.4217 17.9925L10.0352 15.3791L13.7433 16.3203Z");
  stroke: none;
}

.xloahgb9p {
  d: path("M2.7071 21.2929L5.2434 18.7566");
}

</style>
