<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ibmev-tvq"/><path class="lxgltybip"/><path class="ftddq3bvd"/><circle class="hejswn34e"/><path class="yku4ytn5a"/><circle class="l_b48mb3i"/><path class="xs7s5gtpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:living" /></template>
<style>
.ftddq3bvd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.092 23.304c-.077.619-.618 1.16-1.237 1.16a1.018 1.018 0 0 1-1.004-1.16v-.695c.154-.619.695-1.16 1.314-1.16c.618 0 1.082.464 1.005 1.16");
}

.hejswn34e {
  cx: 14.252px;
  cy: 20.599px;
  r: 0.75px;
  fill: currentColor;
}

.ibmev-tvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 20.444v6.184h3.092m6.411-4.174l-1.546 4.174l-1.546-4.174m14.099.155v4.638a1.55 1.55 0 0 1-1.546 1.546c-.464 0-.85-.155-1.082-.464");
}

.l_b48mb3i {
  cx: 20.662px;
  cy: 20.599px;
  r: 0.75px;
  fill: currentColor;
}

.lxgltybip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.464 22.531zc.85 0 1.546.696 1.546 1.546v1.005a1.55 1.55 0 0 1-1.546 1.546a1.55 1.55 0 0 1-1.546-1.546v-1.005c0-.85.696-1.546 1.546-1.546m-3.051 4.097v-2.55a1.55 1.55 0 0 0-1.546-1.547a1.55 1.55 0 0 0-1.546 1.546m0 2.551v-4.174m14.003-1.005s-.154 1.855-.232 2.551c0 .464.464.696.85.696c.928 0 1.47-.85 1.547-2.01c.154-2.397-1.314-3.479-3.324-3.479s-3.402 1.469-3.634 3.479c-.154 1.7.773 3.942 3.17 3.942c1.093 0 1.546 0 2.087-.464");
}

.xs7s5gtpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.662 22.454v4.174M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.yku4ytn5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.252 22.454v4.174");
}

</style>
