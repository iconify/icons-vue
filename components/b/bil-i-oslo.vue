<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w919wby9x"/><path class="yvmw0cc2p"/><circle class="wpy362b-u"/><circle class="kbhh42bxl"/><path class="i1xbaubwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bil-i-oslo" /></template>
<style>
.i1xbaubwa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.587 35.435v6.994h-4.483l-2.51-6.994");
}

.kbhh42bxl {
  cx: 34.929px;
  cy: 26.679px;
  r: 2.271px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w919wby9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.922 19.969h30.156a3.424 3.424 0 0 1 3.422 3.422v12.045h-37V23.39a3.424 3.424 0 0 1 3.422-3.422");
}

.wpy362b-u {
  cx: 13.609px;
  cy: 26.679px;
  r: 2.271px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yvmw0cc2p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.413 35.435v6.994h4.483l2.51-6.994m24.261-15.466l-3.453-11.66a3.82 3.82 0 0 0-3.665-2.738h-14.56a3.82 3.82 0 0 0-3.665 2.737L9.871 19.97");
}

</style>
