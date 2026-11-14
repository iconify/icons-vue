<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jo5xq4b-f"/><path class="ut-7gmbbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-gel-sheet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jo5xq4b-f {
  d: path("M4.5 7H15a1.5 1.5 0 0 1 1.5 1.5v11A1.5 1.5 0 0 1 15 21H7.621a1.5 1.5 0 0 1-1.06-.439l-3.122-3.122A1.5 1.5 0 0 1 3 16.379V8.5A1.5 1.5 0 0 1 4.5 7");
}

.ut-7gmbbp {
  d: path("m8.5 7l1-4.5l12 2.5l-2.75 13l-2.25-.5m-9.5-1l5.5-5.5");
}

</style>
