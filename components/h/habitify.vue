<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wan66_bop"/><path class="v2u_fl71t"/><circle class="psieldboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:habitify" /></template>
<style>
.psieldboh {
  cx: 13.698px;
  cy: 37.615px;
  r: 4.885px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v2u_fl71t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.814 28.768c4.005-9.345 11.951-11.189 16.656-11.189c4.444 0 12.803 3.404 13.714 17.394c.06.928-1.049 1.458-1.738.835c-9.013-8.154-17.37-9.245-28.632-7.04");
}

.wan66_bop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.814 28.768V6.644c0-.632.512-1.144 1.144-1.144h8.773c.632 0 1.144.512 1.144 1.144v11.784m19.309 16.545v6.383c0 .632-.512 1.144-1.144 1.144h-8.773a1.144 1.144 0 0 1-1.145-1.144v-11.62");
}

</style>
