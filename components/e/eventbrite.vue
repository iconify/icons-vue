<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rrzi0-b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eventbrite" /></template>
<style>
.rrzi0-b5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.819 32.477c-1.33 4.977-5.217 9.12-10.553 10.528c-7.922 2.09-16.038-2.636-18.13-10.558l-2.46-9.323c-2.09-7.922 2.636-16.038 10.558-18.13c7.922-2.09 16.039 2.637 18.13 10.559l1.23 4.661l-28.688 7.572");
}

</style>
