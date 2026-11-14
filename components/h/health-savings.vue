<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fio-7yb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-savings" /></template>
<style>
.fio-7yb6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11c0-4 3.5-6.25 7.5-6.25c3.5 0 6 1.5 7 3.75h2V13l-2 .5c-.5 1.5-1.5 2.5-3 3.25v2.75H14l-.5-2H10l-.5 2H7v-3.25C5.75 15 5 13 5 11Zm0-1c-1.5 0-2.5-1-2-2.25M16.5 9h.01m-5.01-.25v4.5M9.25 11h4.5");
}

</style>
