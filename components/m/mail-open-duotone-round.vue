<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eugnk6b2t"/><path class="ysl_j-bne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-duotone-round" /></template>
<style>
.eugnk6b2t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 22H7a5 5 0 0 1-5-5v-6c.001-2.024 1.888-3.794 3.445-4.832l3-2a6.41 6.41 0 0 1 7.11 0l3 2C20.112 7.206 21.999 8.976 22 11v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22");
}

.ft5dv1b6b {
  fill: none;
}

.ysl_j-bne {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H7a4 4 0 0 1-4-4v-6c0-1.25 1.126-2.75 3-4l3-2a5.41 5.41 0 0 1 6 0l3 2c1.874 1.25 3 2.75 3 4v6a4 4 0 0 1-4 4zM4 10l4 4c.64.64 1.72 1 3 1h2c1.28 0 2.36-.36 3-1l4-4");
}

</style>
