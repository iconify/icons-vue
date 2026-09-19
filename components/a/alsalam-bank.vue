<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wq9y73b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alsalam-bank" /></template>
<style>
.wq9y73b8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.385 7.525A27.58 27.58 0 0 0 15.923 24A27.58 27.58 0 0 0 24 43.5m0-39A27.58 27.58 0 0 1 32.077 24a27.58 27.58 0 0 1-5.462 16.475");
}

</style>
