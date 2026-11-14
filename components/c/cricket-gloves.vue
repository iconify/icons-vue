<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to4luh1il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cricket-gloves" /></template>
<style>
.to4luh1il {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 21.5v-5l-4-4A1.75 1.75 0 0 1 7 10l1.5 1.5V8.25a5.25 5.25 0 0 1 10.5 0V21.5ZM12 3.25V11m3.5-7.75V11m-7 7.25H19");
}

</style>
