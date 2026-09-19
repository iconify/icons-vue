<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ec9a8bbos"/><circle class="vvha2kb_h"/><path class="cy00ddbkl"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cvica" /></template>
<style>
.cy00ddbkl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.825 23.023v5.13m5.727-.975c-.334.583-.96.975-1.679.975h0a1.934 1.934 0 0 1-1.932-1.936V24.96c0-1.07.865-1.936 1.932-1.936h0c.717 0 1.343.39 1.677.971m5.95 2.222c0 1.07-.865 1.936-1.933 1.936h0a1.934 1.934 0 0 1-1.932-1.936V24.96c0-1.07.865-1.936 1.932-1.936h0c1.068 0 1.933.867 1.933 1.936m0 3.193v-5.13");
}

.ec9a8bbos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.622 25.556v.032a2.563 2.563 0 0 1-2.561 2.565h0a2.563 2.563 0 0 1-2.56-2.565v-2.614a2.563 2.563 0 0 1 2.56-2.565h0a2.563 2.563 0 0 1 2.56 2.565v.032m2.218.017v5.13m-.193-7.308l1.353-.484m4.858 2.662l-1.932 5.13l-1.933-5.13");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.vvha2kb_h {
  cx: 25.825px;
  cy: 20.651px;
  r: 0.749px;
  fill: currentColor;
}

</style>
