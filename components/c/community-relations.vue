<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5lmtsoun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:community-relations" /></template>
<style>
.q5lmtsoun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0M2.5 18.5c0-3.25 2-5.5 4.75-5.5c2.149 0 3.841 1.375 4.477 3.527M12.75 6a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m2.75 5.5c.983 0 1.823.095 2.541.245M15.5 14.5h5a1 1 0 0 1 1 1v3.25a1 1 0 0 1-1 1h-3l-2 1.75v-1.75a1 1 0 0 1-1-1V15.5a1 1 0 0 1 1-1");
}

</style>
