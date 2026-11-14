<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jg6c-ttdk"/><path class="n9jg3abso"/><path class="umjmx7rcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cinema-camera-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jg6c-ttdk {
  d: path("M2.75 5.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m5.5 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

.n9jg3abso {
  d: path("M5.125 8h5.75a2.625 2.625 0 0 1 2.625 2.625v2.25a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 2.5 12.875v-2.25A2.625 2.625 0 0 1 5.125 8");
}

.umjmx7rcu {
  d: path("m14.569 9.679l2-.6a1.5 1.5 0 0 1 1.931 1.437v1.968a1.5 1.5 0 0 1-1.931 1.437l-2-.6a1.5 1.5 0 0 1-1.069-1.437v-.768a1.5 1.5 0 0 1 1.069-1.437M14.75 18l2 2L21 15.75");
}

</style>
