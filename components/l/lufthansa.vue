<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xtem_j5rd"/><path class="ho2r03b3x"/><path class="x6frffizm"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lufthansa" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ho2r03b3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.5 20.002a107 107 0 0 0-13.72-.382c-.094 1.904-4.87 5.44-8.025 7.103");
}

.x6frffizm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.573 21.937a91 91 0 0 0-12.882-.359m11.506 2.212a106 106 0 0 0-13.424-.412m11.053 2.204c-8.068-.699-13.207-.6-13.207-.6m-11.482-3.71l.635-1.048s4.605 1.842 6.575 2.731");
}

.xtem_j5rd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.513 32.452C20.506 30.482 15.393 21.399 6.5 19.62");
}

</style>
