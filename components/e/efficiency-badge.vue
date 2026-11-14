<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yzqwonbnk"/><path class="o4p0wvauk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:efficiency-badge" /></template>
<style>
.o4p0wvauk {
  d: path("m12.75 6.5l-2.5 3.75h3.5L11.25 14M8.5 16L7 20.5l1.75-1l1.5 1l.25-3.5m5-1l1.5 4.5l-1.75-1l-1.5 1l-.25-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yzqwonbnk {
  d: path("M18.5 10a2.75 2.75 0 0 1-2 4.5a2.75 2.75 0 0 1-4.5 2a2.75 2.75 0 0 1-4.5-2a2.75 2.75 0 0 1-2-4.5a2.75 2.75 0 0 1 2-4.5a2.75 2.75 0 0 1 4.5-2a2.75 2.75 0 0 1 4.5 2a2.75 2.75 0 0 1 2 4.5Z");
}

</style>
