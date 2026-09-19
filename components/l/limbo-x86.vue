<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uexdphlsj"/><path class="edij8pk2x"/><path class="rd4f0h00b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:limbo-x86" /></template>
<style>
.edij8pk2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.7 8h30v18.4h-30Zm10 21.1l-4 4.9h18l-4-4.9M7.2 37l-2.3 4.5h37.6l-3-4.5Z");
}

.rd4f0h00b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36 37c-2.906-6.762 5.657-.81 5.787-4.043c.122-3.039-7.959-1.947-11.19-1.957");
}

.uexdphlsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6 5.3h35.4v23.8H6Z");
}

</style>
