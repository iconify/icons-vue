<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jp2-dj3ix"/><path class="g241b8iuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-solana-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g241b8iuo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 6h12l-4 4H4zm0 8h12l-4 4H4zm-4-4l4 4m8-4l4 4");
}

.jp2-dj3ix {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 5a1 1 0 0 1 .709 1.705l-.002.002L18.414 9H3.586l3.707-3.707l.001-.002C7.482 5.105 7.736 5 8 5ZM3 10h14.414l3.293 3.293l.002.002c.186.187.291.441.291.705H6.586l-3.295-3.294A1 1 0 0 1 3 10m2.586 5h14.828l-3.707 3.707l-.002.002A1 1 0 0 1 16 19H4a1 1 0 0 1-.709-1.705l.002-.002Z");
}

</style>
