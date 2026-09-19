<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gn0_o_bad"/><path class="opagpfb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chessbook" /></template>
<style>
.gn0_o_bad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 8.627v22.395l18.467 8.462l18.53-8.46V8.516l-18.53 8.204zm18.468 8.093v22.764");
}

.opagpfb4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 19.77l-18.53 8.332l-18.467-8.276m9.23-7.152v22.579m18.499-22.634v22.635");
}

</style>
