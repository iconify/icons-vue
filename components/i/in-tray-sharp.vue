<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okef0ybjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:in-tray-sharp" /></template>
<style>
.okef0ybjv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 13.25h17l-.28 1.47l-.94 5.06l-.28 1.47H4.25l-.28-1.47l-.94-5.06l-.28-1.47zm3.75 4h8m-4-14.5v8m-3.25-3L12 11l3.25-3.25");
}

</style>
