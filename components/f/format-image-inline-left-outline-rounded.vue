<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loee18bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-inline-left-outline-rounded" /></template>
<style>
.loee18bks {
  fill: currentColor;
  d: path("M4 15.442V8.558q0-.343.232-.576t.576-.232h6.884q.343 0 .576.232t.232.576v6.884q0 .344-.232.576t-.576.232H4.808q-.343 0-.576-.232T4 15.442m1-.192h6.5v-6.5H5zm10.77 1q-.213 0-.357-.144t-.144-.357t.144-.356t.356-.143H19.5q.213 0 .356.144t.144.357t-.144.356t-.356.143zM4.5 20q-.213 0-.356-.144T4 19.499t.144-.356T4.5 19h15q.213 0 .356.144t.144.357t-.144.356T19.5 20zm0-15q-.213 0-.356-.144T4 4.499t.144-.356T4.5 4h15q.213 0 .356.144t.144.357t-.144.356T19.5 5z");
}

</style>
