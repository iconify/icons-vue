<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cv1pi4rfp"/><ellipse class="ad62fibui"/><ellipse class="cl22x6bkv"/><path class="ip8at9bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:angband" /></template>
<style>
.ad62fibui {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 14.949px;
  ry: 14.994px;
}

.cl22x6bkv {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.104px;
  ry: 7.127px;
}

.cv1pi4rfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.029 22.947L25.24 3.982a1.617 1.617 0 0 0-2.286-.017l-.006.006l-18.966 18.79a1.617 1.617 0 0 0-.017 2.286l.006.006l18.79 18.965a1.617 1.617 0 0 0 2.286.017l.006-.006L44.018 25.24a1.617 1.617 0 0 0 .017-2.286Z");
}

.ip8at9bdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.235 18.483l-1.666-1.663l-2.899.287l-1.156-3.839m16.105 6.122l1.602-1.723l-.393-2.883l3.794-1.296m-5.623 15.659l1.633 1.7l2.902-.23l1.08 3.861M18.551 28.78L17.1 30.632l.642 2.841l-3.669 1.621");
}

</style>
