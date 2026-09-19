<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rwcnjsbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:comixology" /></template>
<style>
.rwcnjsbdn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.317 24.503l2.28 9.859l-7.907 1.31l-1.043-4.378l-5.699 5.809L4.5 38.971l15.256-15.62l-2.668-11.241l8.137-.946l1.237 5.323l6.039-6.184L43.5 9.029z");
}

</style>
