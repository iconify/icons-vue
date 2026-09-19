<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j8sgmwbdr"/><circle class="jmlhidbdl"/><circle class="x7eufiwda"/><circle class="fvfcgbc-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chatterui" /></template>
<style>
.fvfcgbc-v {
  cx: 40.014px;
  cy: 24px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j8sgmwbdr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.173 2.503A21.5 21.5 0 0 0 5.016 24a21.499 21.499 0 0 0 37.968 13.82l-6.511-5.465a13 13 0 0 1-9.959 4.644c-7.18 0-13-5.82-13-13s5.82-12.998 13-12.998a13 13 0 0 1 9.953 4.648l6.517-5.469a21.5 21.5 0 0 0-16.811-7.677");
}

.jmlhidbdl {
  cx: 23.515px;
  cy: 24px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x7eufiwda {
  cx: 31.764px;
  cy: 24px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
