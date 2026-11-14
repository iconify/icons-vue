<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r8q-nsb6u"/><path class="srs6zgjga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:glucometer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r8q-nsb6u {
  d: path("M11.683 18.322a5.8 5.8 0 0 1-2.183.428c-3.25 0-6-2.75-6-6c0-3.5 3-6.5 6-10.25c2.688 3.36 5.376 6.118 5.906 9.172m1.719 2.578h1.75a2.625 2.625 0 0 1 2.625 2.625v2.25a2.625 2.625 0 0 1-2.625 2.625h-1.75a2.625 2.625 0 0 1-2.625-2.625v-2.25a2.625 2.625 0 0 1 2.625-2.625");
}

.srs6zgjga {
  d: path("M17.25 15.75h1.5A1.25 1.25 0 0 1 20 17a1.25 1.25 0 0 1-1.25 1.25h-1.5A1.25 1.25 0 0 1 16 17a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
