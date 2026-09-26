<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xj9aiubci"/><path class="cht9ek43g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-up-sharp-two-tone" /></template>
<style>
.cht9ek43g {
  d: path("M12 6L5 18L19 18L12 6Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xj9aiubci {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.1362 5.4961C11.5221 4.8346 12.4779 4.8346 12.8638 5.4961L19.8638 17.4961C20.2527 18.1628 19.7718 19 19 19L5 19C4.2282 19 3.7473 18.1628 4.1362 17.4961L11.1362 5.4961Z");
  stroke: none;
}

</style>
