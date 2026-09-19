<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ww7x6ubhm"/><path class="h35kaed3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-mail-alt" /></template>
<style>
.h35kaed3d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 31.445l19.5-14.45v-3.6a3.94 3.94 0 0 0-6.28-3.16L24 20.055l-13.22-9.82a3.94 3.94 0 0 0-6.28 3.16v3.6z");
}

.ww7x6ubhm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.39 12.145v26.39H7.06a2.56 2.56 0 0 1-2.56-2.54v-19.18m30.11-4.67v26.39h6.33a2.56 2.56 0 0 0 2.56-2.54v-19.18");
}

</style>
