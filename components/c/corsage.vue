<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x7fwm0bve"/><path class="x2j82-tnh"/><path class="zg1hwg6vs"/><path class="l9vxidbee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corsage" /></template>
<style>
.l9vxidbee {
  d: path("m12 16.5l-3.5-2.25v4.5Zm0 0l3.5-2.25v4.5Zm0 0l-2 5m2-5l2 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x2j82-tnh {
  d: path("M9.25 9.75C7.5 12 5 12.5 3 11.5c1.25-2 3.75-2.75 6.25-1.75Zm5.5 0C16.5 12 19 12.5 21 11.5c-1.25-2-3.75-2.75-6.25-1.75Z");
}

.x7fwm0bve {
  d: path("M15.5 7.25a1.75 1.75 0 0 1-1.75 3a1.75 1.75 0 0 1-3.5 0a1.75 1.75 0 0 1-1.75-3a1.75 1.75 0 0 1 1.75-3a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1 1.75 3Z");
}

.zg1hwg6vs {
  fill: currentColor;
  d: path("M12 7.25h.01");
}

</style>
