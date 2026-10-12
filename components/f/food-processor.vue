<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="jdsfbrben"/><path class="kn0_h_bwo"/><rect class="uxzuo10sf"/><path class="rhj7-w4rz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:food-processor" /></template>
<style>
.jdsfbrben {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6.25v-3.5h3.5v3.5m-6.75 9.5v-8a1.5 1.5 0 0 1 1.5-1.5h8.5a1.5 1.5 0 0 1 1.5 1.5v8Zm11.5-8h2A1.25 1.25 0 0 1 19.5 9v1.5a1.25 1.25 0 0 1-1.25 1.25h-2");
}

.kn0_h_bwo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 11.75c1.5-1.75 3.25-1.5 3.25-.75s1.75 1 3.25-.75");
}

.rhj7-w4rz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18.5h.01");
}

.uxzuo10sf {
  width: 15.5px;
  height: 5.5px;
  x: 4.25px;
  y: 15.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
