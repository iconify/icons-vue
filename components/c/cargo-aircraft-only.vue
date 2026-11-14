<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rzl5atbza"/><path class="b0nv-7bjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cargo-aircraft-only" /></template>
<style>
.b0nv-7bjy {
  d: path("M12 7c.5 0 .75.5.75 1v2.5l3.25 2v1l-3.25-1V15L14 16v1l-2-.5l-2 .5v-1l1.25-1v-2.5L8 13.5v-1l3.25-2V8c0-.5.25-1 .75-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rzl5atbza {
  d: path("M7 4.5h10A3.5 3.5 0 0 1 20.5 8v8a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 16V8A3.5 3.5 0 0 1 7 4.5");
}

</style>
