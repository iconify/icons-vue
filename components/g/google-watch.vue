<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wn9edfbhg"/><path class="cbi50nbic"/><circle class="ui1zimbxa"/><path class="fq0n7eept"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-watch" /></template>
<style>
.cbi50nbic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.432 12.453l-1.31-5.674A2.94 2.94 0 0 0 28.256 4.5h-8.513a2.94 2.94 0 0 0-2.865 2.279l-1.31 5.67m0 23.099l1.31 5.673a2.94 2.94 0 0 0 2.865 2.28h8.513a2.94 2.94 0 0 0 2.865-2.28l1.311-5.674");
}

.fq0n7eept {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 24.477l6.617-4.879m-10.935 1.626L24 24.477m-10.112 9.635a1.9 1.9 0 1 1 2.687-2.687m-2.687-17.537a1.9 1.9 0 1 1 2.687 2.687m17.537-2.687a1.9 1.9 0 1 1-2.687 2.687m2.756 17.466a1.9 1.9 0 0 1-2.705-2.668");
}

.ui1zimbxa {
  cx: 24px;
  cy: 24px;
  r: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wn9edfbhg {
  cx: 24px;
  cy: 24px;
  r: 14.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
