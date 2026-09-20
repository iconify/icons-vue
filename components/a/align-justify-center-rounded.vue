<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shl8wbb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-justify-center-rounded" /></template>
<style>
.shl8wbb-c {
  fill: currentColor;
  d: path("M11.643 20.856q-.143-.143-.143-.356v-17q0-.213.144-.356T12.001 3t.356.144t.143.356v17q0 .213-.144.356t-.357.144t-.356-.144m3.895-4.356q-.343 0-.575-.232t-.232-.576V8.308q0-.343.232-.576t.576-.232h.384q.343 0 .576.232t.232.576v7.384q0 .344-.232.576t-.576.232zm-7.461 0q-.343 0-.576-.232t-.232-.576V8.308q0-.343.232-.576t.576-.232h.385q.343 0 .575.232t.232.576v7.384q0 .344-.232.576t-.576.232z");
}

</style>
