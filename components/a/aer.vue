<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lnh2-j0ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aer" /></template>
<style>
.lnh2-j0ip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.672 19.172A4 4 0 1 1 37.5 26h-29m-2 8h29a4.25 4.25 0 1 1-3.005 7.255M18.257 7.257A6 6 0 1 1 22.499 17.5h-16");
}

</style>
