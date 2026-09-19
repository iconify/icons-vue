<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a3oqb15ij"/><path class="f2m_b3bcs"/><circle class="gpzzzi8kx"/><path class="x2n1rtb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hexviewer" /></template>
<style>
.a3oqb15ij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.18 21.252V15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2v-9.717M28.18 4.5l11 11");
}

.f2m_b3bcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.586 18.028a2.844 2.844 0 0 0-3.905.867l-9.115 14.314l-.653 6.291l5.424-3.252l9.116-14.315a3.09 3.09 0 0 0-.867-3.905M31.566 33.21l4.771 3.038M11.98 39.4h3.4m-3.4-6.8h3.4m-3.4 3.4h2.217m-2.217-3.4v6.8m5.6 0h3.4m-3.4-6.8h3.4m-3.4 3.4h2.217m-2.217-3.4v6.8m8.6-6.8h3.4m-3.4 3.4h2.217m-2.217-3.4v6.8m0-30.86h2m-2 3.4h2m-2-3.4v6.8m-14.5-.06l2.042-6.78m1.958 6.8l-1.958-6.8m1.303 4.525h-2.666m4.921 2.295l2.042-6.78m1.958 6.8l-1.958-6.8m1.303 4.525h-2.666M32.501 27.33l2.042-6.78m1.583 5.497l-1.583-5.497m1.303 4.525H33.18m-21.2 2.265h3.4m-3.4-5.875l1.7-.925m0 0v6.8");
}

.gpzzzi8kx {
  cx: 19.832px;
  cy: 25.087px;
  r: 2.252px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x2n1rtb1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.886 21.37a2.2 2.2 0 0 0-1.895-.83h-.159a2.253 2.253 0 0 0-2.252 2.252v2.295m8.6-2.295a2.253 2.253 0 1 1 4.505 0a2.1 2.1 0 0 1-.66 1.593c-.911.8-3.845 2.955-3.845 2.955h4.505");
}

</style>
