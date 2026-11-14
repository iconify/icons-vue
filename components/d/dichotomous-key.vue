<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dntcz5p8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dichotomous-key" /></template>
<style>
.dntcz5p8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.061 3.561l2.378 2.378a1.5 1.5 0 0 1 0 2.122l-2.378 2.378a1.5 1.5 0 0 1-2.122 0L8.561 8.061a1.5 1.5 0 0 1 0-2.122l2.378-2.378a1.5 1.5 0 0 1 2.122 0M12 11.5v3M5 18v-3.5h14V18M5 21h.01M19 21h.01");
}

</style>
