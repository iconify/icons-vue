<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mftiunbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hdfc-bank" /></template>
<style>
.mftiunbqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30 18H18v12h12zm12.5 3V9.5a4 4 0 0 0-4-4H27m-6 0H9.5a4 4 0 0 0-4 4V21m0 6v11.5a4 4 0 0 0 4 4H21m6 0h11.5a4 4 0 0 0 4-4V27");
}

</style>
