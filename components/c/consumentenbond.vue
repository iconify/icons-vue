<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r_g9gkb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:consumentenbond" /></template>
<style>
.r_g9gkb-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.477 35.485L42.762 16.55c1.641-1.797.366-4.687-2.067-4.687H7.305c-2.433 0-3.708 2.89-2.067 4.687l17.285 18.934a2 2 0 0 0 2.954 0");
}

</style>
