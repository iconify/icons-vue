<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wqbv_qeoq"/><g class="w34osu__y"><circle class="t7jjbjbxs"/><circle class="v-mf_cgpm"/><circle class="l-_lbsl0o"/></g><path class="wlib33hrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:location-share" /></template>
<style>
.l-_lbsl0o {
  cx: 27.252px;
  cy: 19.262px;
  r: 1.23px;
}

.t7jjbjbxs {
  cx: 27.252px;
  cy: 11.671px;
  r: 1.23px;
}

.v-mf_cgpm {
  cx: 19.834px;
  cy: 15.466px;
  r: 1.23px;
}

.w34osu__y {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.wlib33hrp {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("m20.929 14.906l5.229-2.675m-5.229 3.795l5.229 2.676");
}

.wqbv_qeoq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c0-9.447 11.326-19.5 11.326-27.674C35.326 9.571 30.256 4.5 24 4.5c-6.255 0-11.326 5.071-11.326 11.326C12.674 24 24 34.052 24 43.5");
}

</style>
