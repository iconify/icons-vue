<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zoej7biec"/><path class="fu_tz-0kn"/><path class="vmq5s6bzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chest-pain" /></template>
<style>
.fu_tz-0kn {
  fill: currentColor;
  d: path("m13.25 7.25l.25 3l3 .25l-2.25 1.75l1 2.75l-2.75-1l-1.75 2.25l-.25-3l-3-.25l2.25-1.75l-1-2.75l2.75 1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vmq5s6bzf {
  d: path("m5.75 16l1.5 1m11-1l-1.5 1");
}

.zoej7biec {
  d: path("M9.5 2.5c0 1.75-1.25 2.5-3 3L5 6c-1.25.5-1.75 1.25-1.5 2.5l2.25 5c.25 1-.5 4-.5 8h13.5c0-4-.75-7-.5-8l2.25-5c.25-1.25-.25-2-1.5-2.5l-1.5-.5c-1.75-.5-3-1.25-3-3");
}

</style>
