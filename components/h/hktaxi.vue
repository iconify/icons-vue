<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m0hftebut"/><path class="e0hyh8b5f"/><rect class="l34fhilij"/><path class="fxx9_lbsp"/><path class="m5zkhciff"/><rect class="mivy-dbft"/><path class="h03lubbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hktaxi" /></template>
<style>
.e0hyh8b5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.525 20.659v-8.174m-8.079 0l5.415 8.174m0-8.174l-5.415 8.174m-2.788-2.708h-3.621m-.897 2.708l2.707-8.174l2.708 8.174m-11.949-8.174h5.415m-2.708 8.174v-8.174m20.521 16.069v3.103c0 2.758 2.817 4.394 2.817 4.394m-8.436-5.945h8.084m-8.96 2.533h9.836m-6.815-4.085v3.103c0 2.758-2.817 4.394-2.817 4.394");
}

.fxx9_lbsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.122 38.037h8.407m-4.204-3.898V29.33m-5.962 2.206h11.925M8.825 35.26c2.62-.932 6.57-3.724 6.57-3.724");
}

.h03lubbus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.351 38.654c-.117.945-.399 1.928-1.012 1.928h-5.1c-.38 0-.97-.331-.97-1.188c0-.733-.009-1.537-.009-2.269");
}

.l34fhilij {
  width: 8.406px;
  height: 4.593px;
  x: 11.122px;
  y: 35.74px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.791px;
  ry: 0.791px;
}

.m0hftebut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.6 7.224h17.686c7.899 0 11.75 18.696 7.392 18.696H7.073c-3.851 0-.487-18.696 8.527-18.696");
}

.m5zkhciff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.964 35.26c-2.62-.932-6.57-3.724-6.57-3.724m4.341-3.068c-2.999.862-6.463.93-9.049.93m16.131-.643c.818.312 1.753 1.412 1.753 1.412m-2.279 2.071c.818.311 1.753 1.411 1.753 1.411m0 2.309c-.088 1.947-1.607 4.818-1.607 4.818");
}

.mivy-dbft {
  width: 5.471px;
  height: 2.472px;
  x: 31.26px;
  y: 35.333px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.68px;
  ry: 0.68px;
}

</style>
