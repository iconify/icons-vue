<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4h1y5b9l"/><path class="an_0dcczg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:file-folder" /></template>
<style>
.an_0dcczg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14 23.09c0-.85.689-1.539 1.539-1.539h4.47c.428 0 .845.134 1.193.382l2.52 1.8c.347.249.764.382 1.192.382h7.547c.85 0 1.539.69 1.539 1.539V35.91c0 .85-.689 1.539-1.538 1.539H15.538c-.85 0-1.538-.69-1.538-1.539z");
}

.r4h1y5b9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2zm-11-11l11 11");
}

</style>
