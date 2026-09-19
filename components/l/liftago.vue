<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a5rn0_b9l"/><path class="q51axxzzz"/><rect transform="matrix(-1 0 0 -1 59.9 48.434)" class="iyy5jmwxu"/><rect class="ftl94mebr"/><circle class="rky3f_7gc"/><path class="b04byvbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:liftago" /></template>
<style>
.a5rn0_b9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 34.588a49.6 49.6 0 0 1 15.78-2.616c1.631 3.105 5.255 4.065 9.327 4.079a49.2 49.2 0 0 0 12.07-1.818L43.5 13.414a48.5 48.5 0 0 1-15.87 2.825c-1.175-1.984-4.681-4.29-11.497-4.29A41.3 41.3 0 0 0 4.5 14.032");
}

.b04byvbzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.424 21.662v5.11m12.586-1.928a1.93 1.93 0 0 1-1.929 1.928h0a1.93 1.93 0 0 1-1.928-1.928V23.59a1.93 1.93 0 0 1 1.928-1.929h0a1.93 1.93 0 0 1 1.929 1.929m0 3.182v-5.11m-6.473-1.592v5.738a.964.964 0 0 0 .964.964h.29m-4.414.001v-6.366a1.35 1.35 0 0 1 1.35-1.35h0a2.6 2.6 0 0 1 .436.034m-2.917 2.571h5.304");
}

.ftl94mebr {
  width: 3.857px;
  height: 5.111px;
  x: 33.835px;
  y: 21.662px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.929px;
}

.iyy5jmwxu {
  width: 3.857px;
  height: 5.111px;
  x: 28.021px;
  y: 21.662px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.929px;
}

.q51axxzzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.692 19.058v7.714h3.857m20.33-5.11v5.785a1.93 1.93 0 0 1-1.929 1.929h0a1.92 1.92 0 0 1-1.364-.565");
}

.rky3f_7gc {
  cx: 13.424px;
  cy: 19.299px;
  r: 0.675px;
  fill: currentColor;
}

</style>
