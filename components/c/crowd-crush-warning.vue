<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r60n-796e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crowd-crush-warning" /></template>
<style>
.r60n-796e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM3 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm14 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2.5 21v-2.5q-.005-.251.026-.5t.097-.491t.165-.472q.1-.23.232-.443q.131-.214.292-.406t.347-.36t.395-.308q.209-.139.435-.247t.466-.183q.239-.075.487-.115q.247-.04.498-.044t.5.027t.49.098t.472.168t.443.232q.213.133.405.294q.053-.142.116-.281q.064-.138.138-.27q.074-.133.157-.26q.084-.127.177-.247t.195-.233t.212-.217q.111-.105.228-.201t.243-.183t.256-.164t.267-.144t.278-.123t.286-.102t.293-.08t.299-.057t.301-.035q.152-.011.304-.011q.235 0 .469.027q.233.028.462.083q.228.054.449.135q.22.082.43.188t.405.236t.375.283t.339.324t.299.362m5.527 1.49q.185.237.327.501q.143.265.238.55t.141.582t.039.597V21M18 14.5V18m0 3h.01");
}

</style>
