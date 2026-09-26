<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bdvc_jw9o"/><path class="of52wgbuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:link-2-sharp-two-tone" /></template>
<style>
.bdvc_jw9o {
  stroke-opacity: 0.4;
  d: path("M10 17L7 17C4.2386 17 2 14.7614 2 12C2 9.2386 4.2386 7 7 7L10 7M14 7L17 7C19.7614 7 22 9.2386 22 12C22 14.7614 19.7614 17 17 17L14 17");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.of52wgbuj {
  d: path("M7 12L17 12");
}

</style>
