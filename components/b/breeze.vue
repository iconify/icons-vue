<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kme_1ab3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:breeze" /></template>
<style>
.kme_1ab3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.5 5.5C29.851 5.5 35 10.649 35 17s-5.149 11.5-11.5 11.5H13a7 7 0 1 0 0 14h17.5C36.851 42.5 42 37.351 42 31s-5.149-11.5-11.5-11.5H13a7 7 0 1 1 0-14z");
}

</style>
