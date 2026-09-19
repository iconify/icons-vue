<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="afxn1lotk"/><path class="he0znwbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:destiny" /></template>
<style>
.afxn1lotk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 33.12V2.5l16.37 35.442zm0 0V2.5L7.63 37.942z");
}

.he0znwbih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.879 0 21.5 9.621 21.5 21.5S35.879 45.5 24 45.5S2.5 35.879 2.5 24S12.121 2.5 24 2.5");
}

</style>
