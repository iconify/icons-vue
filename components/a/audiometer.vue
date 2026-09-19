<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cfzj0cqca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audiometer" /></template>
<style>
.cfzj0cqca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M6.63 36.5h34.74a.12.12 0 0 1 .13.12v6.76a.12.12 0 0 1-.13.12H6.63a.12.12 0 0 1-.13-.12v-6.76a.12.12 0 0 1 .13-.12Zm0-32h34.74a.12.12 0 0 1 .13.12v6.76a.12.12 0 0 1-.13.12H6.63a.12.12 0 0 1-.13-.12V4.62a.12.12 0 0 1 .13-.12Zm0 21.33h34.74a.13.13 0 0 1 .13.12v6.76a.12.12 0 0 1-.13.12H6.63a.12.12 0 0 1-.13-.12V26a.13.13 0 0 1 .13-.17Zm0-10.66h34.74a.12.12 0 0 1 .13.12v6.76a.13.13 0 0 1-.13.12H6.63a.13.13 0 0 1-.13-.12v-6.76a.12.12 0 0 1 .13-.12Z");
}

</style>
