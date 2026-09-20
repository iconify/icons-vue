<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="v556d3bcq"/><path class="qfvpxpbvf"/><circle class="t2001gbkh"/><path class="htby9ob_t"/><path class="b7f45nx7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fisheyevideo" /></template>
<style>
.b7f45nx7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.245 29.546s4.245-3.304 3.932-8.67c-.314-5.368-2.044-7.155-2.044-7.155s-1.897 1.73 2.01 8.696");
}

.htby9ob_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.088 29.052s-4.166-6.093-10.22-1.022s5.11 8.176 5.11 8.176s7.767.762 5.11-7.154");
}

.qfvpxpbvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 3.5v5.11m0 35.89v-5.11M34.22 7.588l-2.043 3.067M13.78 40.412l2.044-3.066m-.001-26.566l-1.842-3.192M32.177 37.22l1.842 3.192");
}

.t2001gbkh {
  cx: 38.565px;
  cy: 11.235px;
  r: 0.75px;
  fill: currentColor;
}

.v556d3bcq {
  cx: 24px;
  cy: 23.941px;
  r: 15.331px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
