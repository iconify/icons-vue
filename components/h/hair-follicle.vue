<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l4i_rrd9h"/><path class="m4_6ybbpc"/><path class="b6z6fl-2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-follicle" /></template>
<style>
.b6z6fl-2e {
  d: path("M12 14.75V6.5c0-1.75.75-3 2.5-4");
}

.l4i_rrd9h {
  d: path("M2.5 8h6.75m5.5 0h6.75M9.25 8v8c0 3.75 5.5 3.75 5.5 0V8");
}

.m4_6ybbpc {
  fill: currentColor;
  d: path("M10.5 16.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
