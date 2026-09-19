<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t-x52v-cg"/><path class="vty0k1b0b"/><circle class="tj9v4cmon"/><circle class="s61mywbyg"/><circle class="arhqp6n2g"/><circle class="b6ew_kb-a"/><circle class="b-z26ei2a"/><circle class="vdmbvqbbf"/><circle class="ezjv9ubkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:game-launcher" /></template>
<style>
.arhqp6n2g {
  cx: 33.75px;
  cy: 19.774px;
  r: 6.607px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.b-z26ei2a {
  cx: 37.152px;
  cy: 19.774px;
  r: 0.75px;
  fill: currentColor;
}

.b6ew_kb-a {
  cx: 30.348px;
  cy: 19.774px;
  r: 0.75px;
  fill: currentColor;
}

.ezjv9ubkw {
  cx: 33.75px;
  cy: 23.176px;
  r: 0.75px;
  fill: currentColor;
}

.s61mywbyg {
  cx: 14.25px;
  cy: 19.774px;
  r: 6.607px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t-x52v-cg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.163 26.948a9.7 9.7 0 0 0 6.587 2.576c5.385 0 9.75-4.365 9.75-9.75s-4.365-9.75-9.75-9.75a9.7 9.7 0 0 0-6.062 2.122h-7.376a9.7 9.7 0 0 0-6.062-2.122c-5.385 0-9.75 4.365-9.75 9.75s4.365 9.75 9.75 9.75a9.7 9.7 0 0 0 6.587-2.576z");
}

.tj9v4cmon {
  cx: 14.25px;
  cy: 19.774px;
  r: 3.003px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vdmbvqbbf {
  cx: 33.75px;
  cy: 16.372px;
  r: 0.75px;
  fill: currentColor;
}

.vty0k1b0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 19.774v12.645a5.557 5.557 0 0 1-5.557 5.557c-1.26 0-2.496-.336-3.343-1.144c-1.545-1.473-4.625-4.474-6.162-5.97a2.4 2.4 0 0 0-1.676-.681h-5.524c-.626 0-1.227.244-1.676.68c-1.537 1.497-4.617 4.498-6.162 5.971c-.847.808-2.082 1.144-3.343 1.144A5.557 5.557 0 0 1 4.5 32.419V19.774");
}

</style>
