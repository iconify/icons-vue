<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c72its8uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cute-cat" /></template>
<style>
.c72its8uf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 9l.5-5.5l4.5 3a8 8 0 0 1 4 0l4.5-3L19 9A8 8 0 1 1 5 9m4 3h.01M15 12h.01M12 15h.01");
}

</style>
