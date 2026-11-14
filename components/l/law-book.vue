<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n13x6dbmu"/><path class="e0m4uhb8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:law-book" /></template>
<style>
.e0m4uhb8r {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5M12 5v8M8.25 7h7.5m-7.5 0l-1.5 3a1.5 1.5 0 0 0 3 0Zm7.5 0l-1.5 3a1.5 1.5 0 0 0 3 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n13x6dbmu {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19");
}

</style>
