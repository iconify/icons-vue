<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujo29xb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-center-outline-rounded" /></template>
<style>
.ujo29xb5y {
  fill: currentColor;
  d: path("M3.5 12.5q-.213 0-.356-.144T3 11.999t.144-.356t.356-.143h17q.213 0 .356.144t.144.357t-.144.356t-.356.143zm4.808-3q-.343 0-.576-.232T7.5 8.692v-.384q0-.344.232-.576t.576-.232h7.384q.344 0 .576.232t.232.576v.384q0 .343-.232.576t-.576.232zm0 7q-.343 0-.576-.232t-.232-.576v-.384q0-.343.232-.576t.576-.232h7.384q.344 0 .576.232t.232.576v.384q0 .344-.232.576t-.576.232z");
}

</style>
