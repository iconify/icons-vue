<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="timnc2w9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:krungthai-business" /></template>
<style>
.timnc2w9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.01 4.5l3.327 6.985M10.663 43.5l8.153-27.009l5.733 19.384L34.01 4.5l-6.456 5.705");
}

</style>
