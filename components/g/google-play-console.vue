<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="blhy2lbty"/><g class="y9tr6bcfx"><circle class="cxyu9kb9o"/><circle class="usxcybbkh"/><circle class="za04jgofa"/><circle class="rjg065b0r"/><path class="t_z110e_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-play-console" /></template>
<style>
.blhy2lbty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.055 27.738c1.35-.727 2.284-2.18 2.284-3.738c-.104-1.557-1.038-3.01-2.388-3.738L15.202 5.623C14.58 5.208 13.75 5 12.918 5C10.945 5 9.18 6.35 8.765 8.115c-.104.311-.104.727-.104 1.142v29.59c0 .415 0 .727.104 1.142v-.104C9.285 41.65 10.945 43 12.918 43q1.245 0 2.18-.623z");
}

.cxyu9kb9o {
  cx: 14.57px;
  cy: 29px;
  r: 1.804px;
}

.rjg065b0r {
  cx: 33.43px;
  cy: 21.65px;
  r: 1.804px;
}

.t_z110e_f {
  d: path("m15.846 27.724l3.62-3.62m8.059 2.697l4.574-3.939m-10.113 1.271l2.964 2.576");
}

.usxcybbkh {
  cx: 20.742px;
  cy: 22.828px;
  r: 1.804px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.za04jgofa {
  cx: 26.194px;
  cy: 28.014px;
  r: 1.804px;
}

</style>
