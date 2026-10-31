<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rlq1_8btq"/><path class="wxs766d_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:air-vent-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rlq1_8btq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2L19 2C21.2092 2 23 3.7908 23 6L23 10C23 12.2092 21.2092 14 19 14L5 14C2.7908 14 1 12.2092 1 10L1 6C1 3.7908 2.7908 2 5 2Z");
  stroke: none;
}

.wxs766d_r {
  d: path("M6 9L18 9M14 13L14 19C14 20.1046 14.8954 21 16 21C17.1046 21 18 20.1046 18 19L18 18M9.5 13L9.5 17C9.5 18.1046 8.6046 19 7.5 19C6.3954 19 5.5 18.1046 5.5 17");
}

</style>
