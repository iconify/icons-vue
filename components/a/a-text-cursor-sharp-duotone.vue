<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qv42ivz-f"/><path class="zreesg9no"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:a-text-cursor-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qv42ivz-f {
  stroke-opacity: 0.4;
  d: path("M1.93 18.6273L7.002 6L12.074 18.6273M4.19 13H9.813");
}

.zreesg9no {
  d: path("M19 6.8C18.667 6.35 17.6 5 16 5H15M19 6.8C19.333 6.35 20.4 5 22 5H23M19 6.8V17.2M19 17.2C19.333 17.65 20.4 19 22 19H23M19 17.2C18.667 17.65 17.6 19 16 19H15");
}

</style>
