<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h2h1kccpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cnn" /></template>
<style>
.h2h1kccpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 15.935v16.13l-12.56-16.13v16.13l-12.56-16.13v16.13h-5.815a8.065 8.065 0 0 1 0-16.13h2.829");
}

</style>
