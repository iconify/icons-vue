<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wryfj1kjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lunch-dining" /></template>
<style>
.wryfj1kjd {
  fill: currentColor;
  d: path("M4.616 20q-.672 0-1.144-.472T3 18.385v-2.77h18v2.77q0 .67-.472 1.143q-.472.472-1.143.472zm6.026-6.884q-.476.5-1.646.5t-1.64-.5t-1.352-.5t-1.358.5q-.477.5-1.646.5v-1q.88 0 1.358-.5q.476-.5 1.646-.5t1.64.5t1.352.5t1.358-.5t1.646-.5t1.646.5t1.358.5t1.333-.5t1.62-.5t1.678.5t1.365.5v1q-1.17 0-1.616-.5t-1.326-.5t-1.383.5t-1.671.5t-1.646-.5t-1.358-.5t-1.358.5M3 9.616V9q0-2.356 2.088-3.678T12 4t6.913 1.322T21 9v.616z");
}

</style>
