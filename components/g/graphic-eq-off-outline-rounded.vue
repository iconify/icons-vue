<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rch8cabfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:graphic-eq-off-outline-rounded" /></template>
<style>
.rch8cabfp {
  fill: currentColor;
  d: path("M11.643 20.856q-.143-.143-.143-.356v-7.573l-2.75-2.75v6.439q0 .212-.144.356t-.357.144t-.356-.144t-.143-.356V9.177L3.094 4.521q-.146-.146-.155-.347t.155-.366t.357-.166t.357.166l16.384 16.384q.147.147.156.345t-.156.363t-.356.166t-.357-.166L12.5 13.927V20.5q0 .213-.144.356t-.357.144t-.356-.144m-7.5-7.692Q4 13.02 4 12.808v-1.616q0-.212.144-.356t.357-.144t.356.144t.143.356v1.616q0 .212-.144.356t-.357.144t-.356-.144m7.86-4.183q-.186 0-.344-.13q-.159-.13-.159-.376V3.5q0-.213.144-.356T12.001 3t.356.144t.143.356v4.98q0 .25-.155.376q-.155.125-.342.125m3.75 3.75q-.186 0-.344-.13q-.159-.13-.159-.376v-4.84q0-.213.144-.357t.357-.143t.356.143t.143.357v4.846q0 .25-.155.375t-.341.125m3.39.433Q19 13.02 19 12.808v-1.616q0-.212.144-.356t.357-.144t.356.144t.143.356v1.616q0 .212-.144.356t-.357.144t-.356-.144");
}

</style>
