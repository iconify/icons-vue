<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-wyuigbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-pin-shield" /></template>
<style>
.b-wyuigbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 13.2v8.3h-12v-9.9m6 2.15h.01m2.99 0h.01M5.5 16.5h.01m2.99 0h.01m2.99 0h.01M5.5 19.25h.01m2.99 0h.01m2.99 0h.01M21.5 3h-8C9 3 6 6 5.25 10.25c-.25 1 1 1.5 1.75.75c1.25-1.5 3-2.75 5.5-2.75h2l2 3c.5.75 1.5.5 1.5-.25l-.5-2.75h4m-11.25-2.5l2.25-.5");
}

</style>
