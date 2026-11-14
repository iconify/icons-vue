<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="saxb5le3t"/><path class="pmh6eib_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:audit-log" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pmh6eib_e {
  d: path("M15 17.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m4.25 1.75L21 21");
}

.saxb5le3t {
  d: path("M12.25 21.5H6.5a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v7.75M8 7h6m-6 3.5h6M8 14h1.5");
}

</style>
