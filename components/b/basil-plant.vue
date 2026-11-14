<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jufqt1bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basil-plant" /></template>
<style>
.jufqt1bsx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5v-18M12 16c-3 1-8-.5-8.5-4.5c4-.5 7.5 1 8.5 4.5m0 0c3 1 8-.5 8.5-4.5c-4-.5-7.5 1-8.5 4.5m0-7.5c-2 .5-5.5-.5-6-4c3-.5 5.5 1 6 4m0 0c2 .5 5.5-.5 6-4c-3-.5-5.5 1-6 4");
}

</style>
