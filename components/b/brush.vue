<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfcs405b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brush" /></template>
<style>
.mjfcs405b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.31 4.75l-1.06-1.06q-.53-.53-1.06 0l-6.72 6.72q-.53.53-1.24.36q-.7-.18-1.23.35l-.54.53q-.53.53 0 1.06l2.83 2.83q.53.53 1.06 0l.53-.54q.53-.53.35-1.23q-.17-.71.36-1.24l6.72-6.72q.53-.53 0-1.06m-8.49 11.32l-3.89-3.89c-2.12 2.12-3.88 4.95-3.71 7.6c2.65.17 5.48-1.59 7.6-3.71");
}

</style>
