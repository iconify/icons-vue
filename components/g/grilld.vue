<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wc-g1re6q"/><circle class="wjsepxben"/><path class="dqsh55x6v"/><circle class="v57bw8srr"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:grilld" /></template>
<style>
.dqsh55x6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.204 23.277l1.343 5.29m.923-8.648l1.764 7.053c.084.504.756.923 1.26.755h.335m.252-8.732l1.763 7.053c.084.504.756.924 1.26.756h.336m7.22-5.458c-.335-1.175-1.343-1.763-2.518-1.595c-1.176.336-1.764 1.343-1.596 2.519l.336 1.343c.336 1.176 1.344 1.763 2.519 1.595c1.176-.335 1.763-1.343 1.595-2.518m.504 1.931l-1.931-7.977m-23.761 8.649c-.42-1.428-1.848-2.351-3.275-1.932s-2.35 1.848-1.931 3.275l.588 2.687c.42 1.427 1.847 2.35 3.274 1.93c1.427-.419 2.351-1.846 1.931-3.274l-2.687.588m19.89-8.547c.42-.419.428-.894.336-1.175l-.168-.587");
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

.v57bw8srr {
  cx: 31.524px;
  cy: 18.324px;
  r: 0.75px;
  fill: currentColor;
}

.wc-g1re6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.174 26.384c-.336-1.175.42-2.267 1.595-2.519m-2.099.588l1.343 5.289");
}

.wjsepxben {
  cx: 21.616px;
  cy: 20.843px;
  r: 0.75px;
  fill: currentColor;
}

</style>
