<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tqys-8bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:finn-mobile" /></template>
<style>
.tqys-8bnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 39.315V19.51L24 29.673L42.5 19.51v19.805m-37-30.63L24 18.848L42.5 8.685");
}

</style>
