<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g_hbi7b5g"/><path class="u2cvpabff"/><path class="y5be-cchd"/><circle class="o96bb2bhx"/><circle class="dmlst7ild"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kryptey" /></template>
<style>
.dmlst7ild {
  cx: 24px;
  cy: 18.055px;
  r: 11.536px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g_hbi7b5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.642 20.079h-3.69v4.297h4.299v-2.01m21.498-.12v2.13h4.297v-4.298h-3.688M8.953 26.52v4.307h4.298V26.52zm7.208 0h-.757v4.307h4.298v-1.873m2.144.435v1.439h4.307v-1.439m2.144-.627v2.066h4.298V26.52h-.757m2.91 0v4.308h4.298V26.52zM8.954 32.972v4.297h4.298v-4.297zm6.451 0v4.297h17.191v-4.297zm19.345 0v4.297h4.297v-4.297z");
}

.o96bb2bhx {
  cx: 23.996px;
  cy: 20.03px;
  r: 1.571px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u2cvpabff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.673 15.866H7.398c-1.048 0-1.898.85-1.898 1.898v21.82c0 1.048.85 1.897 1.897 1.897h33.206a1.897 1.897 0 0 0 1.897-1.897v-21.82c0-1.048-.85-1.898-1.897-1.898h-5.276");
}

.y5be-cchd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.613 15.31h10.773a.74.74 0 0 1 .74.74v7.961a.74.74 0 0 1-.74.74H18.613a.74.74 0 0 1-.74-.74V16.05a.74.74 0 0 1 .74-.74m1.332 0v-1.7a4.052 4.052 0 0 1 8.103 0v1.7");
}

</style>
