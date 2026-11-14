<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hb-trubka"/><path class="f3068hb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heat-pack" /></template>
<style>
.f3068hb6c {
  d: path("M8.5 18.5c-1-1.5 1-3 0-4.5s1-3 0-4.25M12 18.5c-1-1.5 1-3 0-4.5s1-3 0-4.25m3.5 8.75c-1-1.5 1-3 0-4.5s1-3 0-4.25");
}

.hb-trubka {
  d: path("M8.75 3h6.5a5.25 5.25 0 0 1 5.25 5.25v7.5A5.25 5.25 0 0 1 15.25 21h-6.5a5.25 5.25 0 0 1-5.25-5.25v-7.5A5.25 5.25 0 0 1 8.75 3M3.5 7h17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
