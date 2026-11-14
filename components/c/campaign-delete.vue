<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcy3_3bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campaign-delete" /></template>
<style>
.dcy3_3bzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.43 16.095L7.5 13.5h-4v-5h4l9.5-5v8.665M6 13.5l1.5 5M15 15h6m-5 0v5.5q0 1 1 1h2q1 0 1-1V15");
}

</style>
