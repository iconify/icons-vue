<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="swg-gcyiy"/><path class="fddrtko1a"/><circle class="on_p_j6re"/><circle class="ed_r8w2vc"/><circle class="pwukoibtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-thermometer" /></template>
<style>
.ed_r8w2vc {
  cx: 29.603px;
  cy: 20.572px;
  r: 0.75px;
  fill: currentColor;
}

.fddrtko1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 27.256c0 2.998 3.834 4.006 3.834 7.643a3.834 3.834 0 1 1-7.668 0c0-3.637 3.834-4.645 3.834-7.643");
}

.on_p_j6re {
  cx: 29.603px;
  cy: 15.288px;
  r: 0.75px;
  fill: currentColor;
}

.pwukoibtf {
  cx: 29.603px;
  cy: 25.855px;
  r: 0.75px;
  fill: currentColor;
}

.swg-gcyiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.603 10.103a5.603 5.603 0 0 0-5.904-5.595c-3.03.158-5.302 2.878-5.302 5.912l-.001 14.92c0 1.639-.47 3.254-1.418 4.59c-1.304 1.84-1.904 4.216-1.404 6.732c.653 3.288 3.293 5.96 6.575 6.645c5.559 1.158 10.452-3.053 10.452-8.408a8.56 8.56 0 0 0-1.229-4.433M24 20.572v6.684");
}

</style>
