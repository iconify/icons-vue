<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tvmx53b0s"/><path class="sxr8ymbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:first-class-carriage" /></template>
<style>
.sxr8ymbck {
  d: path("M5.25 7.5h3v3h-3v-3m5.25 0h3v3h-3v-3m5.85 3h-.6v-3h3v2.3M4 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6.054-.4q-.054.197-.054.4q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T11.5 18q.256 0 .498-.085M17.75 14l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.tvmx53b0s {
  d: path("M9.026 15H2.5V7C2.5 5.5 4 4.5 6 4.5h12c2 0 3.5 1 3.5 2.5v6.674");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
