<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1jhfkb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:live-raise-hand" /></template>
<style>
.x1jhfkb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 10.5V5.75a1.75 1.75 0 0 1 3.5 0v-1.5a1.75 1.75 0 0 1 3.5 0v1.5a1.75 1.75 0 0 1 3.5 0V14a7 7 0 0 1-7 7c-2 0-3.5-1-4.75-2.5l-2.25-3a1.75 1.75 0 0 1 3-2l.5.5Zm3.5-4.75V11M14 5.75V11");
}

</style>
