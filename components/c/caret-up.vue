<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw6ofjypm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:caret-up" /></template>
<style>
.nw6ofjypm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 15.75h12c.9 0 1.35-1.1.7-1.7l-6-5.6a1 1 0 0 0-1.4 0l-6 5.6c-.65.6-.2 1.7.7 1.7");
}

</style>
