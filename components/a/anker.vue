<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tqe-_ubbr"/><path class="dt2f8598c"/><path class="dgg3k9bgy"/><circle class="u49-p7b6e"/><circle class="hwa4wubsx"/><circle class="j36u6hbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anker" /></template>
<style>
.dgg3k9bgy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.252 38.228c-5.681 6.788-13.707.78-15.048 4.465");
}

.dt2f8598c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.547 29.6c-.011 8.852 9.998 9.408 8.657 13.093m16.007-.69c3.47-2.623 3.971-7.3 3.422-10.185c0 0-4.219 4.523-7.444 4.435c2.908 1.115 4.358 2.786 4.022 5.75");
}

.hwa4wubsx {
  cx: 22.446px;
  cy: 12.245px;
  r: 1.683px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j36u6hbeu {
  cx: 38.058px;
  cy: 17.927px;
  r: 1.683px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tqe-_ubbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.477 17.352L24.028 12.82m7.804-2.074L19.91 43.501M8.386 31.876c-.972-4.24 1.65-8.145 3.926-10.003c0 0 .324 6.177 2.852 8.183c-2.946-1.015-5.13-.667-6.778 1.82");
}

.u49-p7b6e {
  cx: 32.763px;
  cy: 8.188px;
  r: 3.688px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
