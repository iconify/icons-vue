<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="denk-1bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-flex-center-outline-rounded" /></template>
<style>
.denk-1bex {
  fill: currentColor;
  d: path("M11.836 20.856q-.144-.143-.144-.356V13H4.308q-.343 0-.576-.232t-.232-.576v-.384q0-.343.232-.576T4.308 11h7.384V3.5q0-.213.144-.356T12.193 3t.356.144t.143.356V11h7q.344 0 .576.232t.232.576v.384q0 .344-.232.576t-.576.232h-7v7.5q0 .213-.144.356q-.143.144-.356.144t-.356-.144");
}

</style>
