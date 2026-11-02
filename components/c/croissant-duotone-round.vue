<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wskexpbkd"/><path class="u0l8-pbha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:croissant-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.u0l8-pbha {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3a9.49 9.49 0 0 0-6 6l8 4l2 1c.64.32 1.32-.36 1-1l-1-2ZM3 9v6a2 2 0 0 0 2 2h5m-5 0c0 2.21 1.343 4 3 4a2 2 0 0 0 2-2v-2c0-1.5.4-3 1-4M9 3h6a2 2 0 0 1 2 2v5m0-5c2.21 0 4 1.343 4 3a2 2 0 0 1-2 2h-2c-1.5 0-3 .4-4 1");
}

.wskexpbkd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 2h6c1.292 0 2.441.83 2.848 2.056c1.473.199 2.959.957 3.709 2.285C21.842 6.848 22 7.417 22 8c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 11h-2a7.8 7.8 0 0 0-2.65.463l.544 1.09a1.74 1.74 0 0 1-.327 2.014a1.74 1.74 0 0 1-2.014.327l-1.09-.544A7.8 7.8 0 0 0 11 17v2c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 8 22a3.4 3.4 0 0 1-1.659-.443c-1.328-.75-2.086-2.236-2.285-3.709A3 3 0 0 1 2 15V9a1 1 0 0 1 .051-.316a10.49 10.49 0 0 1 6.633-6.633A1 1 0 0 1 9 2");
}

</style>
