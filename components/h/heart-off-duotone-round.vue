<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gul0ugb6t"/><path class="zl5m2e4xn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gul0ugb6t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 5.247a6.24 6.24 0 0 1 3.552-1.939c2.656-.469 5.187.78 6.089 3.393c.254.738.359 1.52.359 2.299c-.001 1.72-.645 3.359-1.565 4.791c-.895 1.391-2.038 2.61-3.271 3.706a29 29 0 0 1-3.203 2.46c-.482.321-.969.636-1.475.917a1 1 0 0 1-.972 0a22 22 0 0 1-1.475-.917a29 29 0 0 1-3.203-2.46c-1.233-1.096-2.376-2.315-3.271-3.706C2.645 12.359 2.001 10.72 2 9c0-.779.105-1.561.359-2.299c.902-2.613 3.433-3.862 6.089-3.393A6.24 6.24 0 0 1 12 5.247");
}

.zl5m2e4xn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 5c-1.458.615-3 1.615-3 4c0 6 9 11 9 11s2.556-1.653 5-4m3-3c.703-1.2 1-2.653 1-4c0-5.34-5.37-5.754-8-3M3 2l19 19");
}

</style>
