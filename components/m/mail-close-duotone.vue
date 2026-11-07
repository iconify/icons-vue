<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t706tjvzy"/><path class="cd295hbnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-close-duotone" /></template>
<style>
.cd295hbnn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 13v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h6M4 6l4 4c.64.64 1.36 1 2 1h3m3-7l4 4m0-4l-4 4");
}

.ft5dv1b6b {
  fill: none;
}

.t706tjvzy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M22 17a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h6a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779c.52 1.556 1.603 2.735 3.003 3.551c1.093.638 2.364 1.031 3.638.985a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13Z");
}

</style>
