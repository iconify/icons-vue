<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sizxevc4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ancestral-home" /></template>
<style>
.sizxevc4j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143L9.81 4.132q2.19-1.866 4.38 0l5.875 5.011q1.185 1.011 1.185 2.568v3.809l-.338-.507v-.001Q19.873 13.454 18 13.454t-2.912 1.559l-.697 1.046q-1.163 1.744-.174 3.592q.626 1.169 1.694 1.599H6.125q-3.375 0-3.375-3.375v-6.164q0-1.557 1.185-2.568m16.634 7.609l-.697-1.046q-.668-1.002-1.872-1.002t-1.872 1.002l-.697 1.046q-.748 1.121-.112 2.31q.624 1.164 1.931 1.188v1.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1.5q1.307-.024 1.931-1.188q.636-1.189-.112-2.31m-3.266 1.998h1.394q.449 0 .661-.396t-.037-.77l-.697-1.046q-.223-.334-.624-.334t-.624.334l-.697 1.046q-.249.374-.037.77t.661.396");
}

</style>
