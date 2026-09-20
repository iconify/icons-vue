<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mkl7h9bkq"/><path class="ql1x16bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ig-metall" /></template>
<style>
.mkl7h9bkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 5.5l18.134 37H5.866zm0 4.809v8.968");
}

.ql1x16bko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.915 24.51c0-1.68-1.458-3.138-3.14-3.026c-1.569.112-2.802 1.57-2.802 3.139v2.802A3.014 3.014 0 0 0 24 30.452a3.014 3.014 0 0 0 3.027-3.027H24m-4.484 13.054v-8.968L24 40.479l4.484-8.968v8.968");
}

</style>
