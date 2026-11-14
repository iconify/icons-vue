<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-13mq2fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lightbulb-group" /></template>
<style>
.v-13mq2fc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 9.25a3.5 3.5 0 1 1 2.5 0v1.5h-2.5Zm12 0a3.5 3.5 0 1 1 2.5 0v1.5h-2.5ZM10 17.5a4 4 0 1 1 4 0V19h-4Zm.75 4.25h2.5");
}

</style>
