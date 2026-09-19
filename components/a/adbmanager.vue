<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yl6ujcg9e"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adbmanager" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.yl6ujcg9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.297 14.625v14.097m0-5.851a3.524 3.524 0 0 1 3.525-3.524h0a3.524 3.524 0 0 1 3.524 3.524v2.327a3.524 3.524 0 0 1-3.524 3.524h0a3.524 3.524 0 0 1-3.525-3.525m-3.773-10.572v14.097m0-3.525A3.524 3.524 0 0 1 24 28.722h0a3.524 3.524 0 0 1-3.524-3.525v-2.326A3.524 3.524 0 0 1 24 19.346h0a3.524 3.524 0 0 1 3.524 3.525m-10.821 2.326a3.524 3.524 0 0 1-3.525 3.525h0a3.524 3.524 0 0 1-3.524-3.525v-2.326a3.524 3.524 0 0 1 3.524-3.525h0a3.524 3.524 0 0 1 3.525 3.525m0-3.524v9.375");
}

</style>
