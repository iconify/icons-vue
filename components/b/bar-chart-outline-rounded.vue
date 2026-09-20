<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijy02wtct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bar-chart-outline-rounded" /></template>
<style>
.ijy02wtct {
  fill: currentColor;
  d: path("M16.808 19q-.344 0-.576-.232T16 18.192V15q0-.343.232-.575t.576-.233h1.384q.344 0 .576.232T19 15v3.192q0 .344-.232.576t-.576.232zm-5.5 0q-.344 0-.576-.232t-.232-.576V5.808q0-.343.232-.576T11.308 5h1.384q.344 0 .576.232t.232.576v12.384q0 .344-.232.576t-.576.232zm-5.5 0q-.344 0-.576-.232T5 18.192v-7.567q0-.358.232-.587t.576-.23h1.384q.343 0 .576.232t.232.576v7.567q0 .358-.232.587t-.576.23z");
}

</style>
