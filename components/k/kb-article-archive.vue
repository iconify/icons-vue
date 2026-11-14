<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iqgmv9b7j"/><path class="g97j9x61h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kb-article-archive" /></template>
<style>
.g97j9x61h {
  d: path("M13.5 2.5V6H17M9.5 16.75h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iqgmv9b7j {
  d: path("M2.5 12.5h19M4 12.5V19a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-6.5m-13 0v-8a2 2 0 0 1 2-2h4.5L17 6v6.5");
}

</style>
