<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="x3x6dmp9r"/><path class="zzvn_qs9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:esimcrew" /></template>
<style>
.x3x6dmp9r {
  cx: 34.25px;
  cy: 34.25px;
  r: 8.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zzvn_qs9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5v37h-9.25L5.5 33.25v-18.5l9.25-9.25h18.5l9.25 9.25V24h-37");
}

</style>
