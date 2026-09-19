<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zptdxwmha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dacia" /></template>
<style>
.zptdxwmha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 18.479H28.182L24 22.66l-4.182-4.181H7.5m0 11.042h12.318L24 25.34l4.182 4.181H40.5");
}

</style>
