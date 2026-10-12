<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tr-rgutki"/><path class="cq893l8kp"/><path class="wxvyht8eu"/><path class="ptacfv-ps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eagle-sharp" /></template>
<style>
.cq893l8kp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 6c-2.25.25-4 1.75-4 4.25v1.25l.75.75l.35-1.75H6l2.6-1.8");
}

.ptacfv-ps {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.75 11.75l1.25 2.5v2.25");
}

.tr-rgutki {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.25 9.5c-1.5-3.75-4.5-6.25-8.25-6.25c-2.5 0-4.75 1-6.25 2.75L9 9.25c.5 4.5 1.25 7.5 1.25 12H20C19.5 17.5 18.25 15 17 13c1.25-2 2.75-3 4.25-3.5Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wxvyht8eu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.5 7.25h.01");
}

</style>
