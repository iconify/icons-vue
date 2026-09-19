<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4h1y5b9l"/><path class="nae_oy0hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:file-mail" /></template>
<style>
.nae_oy0hr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.235 22.855a1 1 0 0 0-1 1h0V35.16a1 1 0 0 0 1 1h17.53a1 1 0 0 0 1-1h0V23.84a1 1 0 0 0-1-1h-17.53zm16.605 1.91L24 30.535l-7.84-5.77");
}

.r4h1y5b9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2zm-11-11l11 11");
}

</style>
