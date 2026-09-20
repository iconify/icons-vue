<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0v9ahxrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-stretch-outline-rounded" /></template>
<style>
.y0v9ahxrs {
  fill: currentColor;
  d: path("M8.308 9.5q-.343 0-.576-.232T7.5 8.692V4h-4q-.213 0-.356-.144T3 3.499t.144-.356T3.5 3h17q.213 0 .356.144t.144.357t-.144.356T20.5 4h-4v4.692q0 .344-.232.576t-.576.232zM3.5 21q-.213 0-.356-.144T3 20.499t.144-.356T3.5 20h4v-4.692q0-.344.232-.576t.576-.232h7.384q.344 0 .576.232t.232.576V20h4q.213 0 .356.144t.144.357t-.144.356T20.5 21z");
}

</style>
