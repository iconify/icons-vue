<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okp3czn4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-start-square-outline-rounded" /></template>
<style>
.okp3czn4a {
  fill: currentColor;
  d: path("M4.577 14.923h5.846V9.077H4.577zm-.192 1q-.344 0-.576-.232t-.232-.576v-6.23q0-.344.232-.576t.576-.232h6.23q.344 0 .576.232t.232.576V11.5h9q.213 0 .356.144t.144.357t-.144.356t-.356.143h-9v2.616q0 .343-.232.575t-.575.232zM7.5 12");
}

</style>
