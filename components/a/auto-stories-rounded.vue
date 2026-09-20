<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4270r2nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-stories-rounded" /></template>
<style>
.u4270r2nr {
  fill: currentColor;
  d: path("M11.597 18.408q-.185-.047-.333-.133q-1.102-.644-2.295-.96T6.5 17q-.78 0-1.534.13q-.753.132-1.466.42q-.544.217-1.022-.121T2 16.496V6.87q0-.371.205-.669t.537-.423q.881-.388 1.833-.583T6.5 5q1.47 0 2.847.452T12 6.654v10.869q1.256-.8 2.666-1.161Q16.075 16 17.5 16q.823 0 1.378.064q.555.063 1.545.344q.212.057.394.01q.183-.049.183-.318V5.639q.144.028.276.08t.251.135q.237.125.355.356t.118.506v9.742q0 .594-.507.923q-.506.329-1.108.13q-.695-.269-1.419-.39T17.5 17q-1.296 0-2.527.316q-1.23.315-2.333.959q-.148.087-.324.133t-.355.046t-.364-.046m3.113-4.043q-.212.187-.461.078T14 14.048V6.681q0-.081.038-.168t.093-.144l4.154-4.153q.211-.212.463-.097t.252.408v7.787q0 .105-.04.183t-.097.134z");
}

</style>
