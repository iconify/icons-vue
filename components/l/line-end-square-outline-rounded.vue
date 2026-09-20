<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqii0dtvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-end-square-outline-rounded" /></template>
<style>
.yqii0dtvi {
  fill: currentColor;
  d: path("M13.577 14.923h5.846V9.077h-5.846zm-.192 1q-.344 0-.576-.232t-.232-.576V12.5h-9q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h9V8.885q0-.344.232-.576t.576-.232h6.23q.344 0 .576.232t.232.576v6.23q0 .344-.232.576t-.575.232zM16.5 12");
}

</style>
