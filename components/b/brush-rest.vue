<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j14d5xjre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brush-rest" /></template>
<style>
.j14d5xjre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18.5v-6.75h6l3 3l3-3h6v6.75Zm.5-11H12M12 6c4 0 7 .75 8.5 1.5C19 8.25 16 9 12 9Z");
}

</style>
