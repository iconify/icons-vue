<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swt6eebln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-weeder" /></template>
<style>
.swt6eebln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.682 14.318za2 2 0 0 1 0 2.828l-3.536 3.536a2 2 0 0 1-2.828 0a2 2 0 0 1 0-2.828l3.536-3.536a2 2 0 0 1 2.828 0m.068-.068l3.75-3.75m0 0l2-2L17 3m-1.5 5.5L21 7");
}

</style>
