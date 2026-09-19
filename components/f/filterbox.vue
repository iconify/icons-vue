<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ge36-obtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:filterbox" /></template>
<style>
.ge36-obtg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36 21.5A11.97 11.97 0 0 0 26 9.668V7.5c0-1.108-.892-2-2-2s-2 .892-2 2v2.168A11.97 11.97 0 0 0 12 21.5v11.379l-3.06 3.06A1.5 1.5 0 0 0 10 38.5h28a1.5 1.5 0 0 0 1.06-2.56L36 32.88zm-8 17a4 4 0 1 1-8 0zM16 20h16M21.5 30.672h5m-8-5.336h11");
}

</style>
