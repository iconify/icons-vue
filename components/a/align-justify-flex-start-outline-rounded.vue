<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm61yyb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-justify-flex-start-outline-rounded" /></template>
<style>
.lm61yyb7h {
  fill: currentColor;
  d: path("M3.5 21q-.214 0-.357-.144T3 20.5v-17q0-.213.144-.356T3.501 3t.356.144T4 3.5v17q0 .213-.144.356T3.499 21m10.809-4.5q-.343 0-.576-.232t-.232-.576V8.308q0-.343.232-.576t.576-.232h.384q.344 0 .576.232t.232.576v7.384q0 .344-.232.576t-.576.232zm-6 0q-.343 0-.576-.232t-.232-.576V8.308q0-.343.232-.576t.576-.232h.384q.344 0 .576.232t.232.576v7.384q0 .344-.232.576t-.576.232z");
}

</style>
