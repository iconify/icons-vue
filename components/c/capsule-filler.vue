<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="appxo8bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:capsule-filler" /></template>
<style>
.appxo8bmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.956 2.5h8.088a1.75 1.75 0 0 1 1.19 3.032l-3.175 2.949a1.75 1.75 0 0 0-.559 1.282v.487a1.25 1.25 0 0 1-1.25 1.25h-.5a1.25 1.25 0 0 1-1.25-1.25v-.487a1.75 1.75 0 0 0-.559-1.282L6.766 5.532A1.75 1.75 0 0 1 7.956 2.5m.544 12V18a3.5 3.5 0 0 0 7 0v-3.5");
}

</style>
