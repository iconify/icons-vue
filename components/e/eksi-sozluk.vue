<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fskv5_56t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eksi-sozluk" /></template>
<style>
.fskv5_56t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.533 29.967c0 7.474-6.06 13.533-13.533 13.533s-13.533-6.059-13.533-13.533C10.467 19.094 24 4.5 24 4.5s13.533 14.594 13.533 25.467");
}

</style>
