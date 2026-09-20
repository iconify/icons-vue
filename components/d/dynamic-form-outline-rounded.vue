<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi3bh_h9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dynamic-form-outline-rounded" /></template>
<style>
.fi3bh_h9r {
  fill: currentColor;
  d: path("M4.116 11q-.667 0-1.141-.475T2.5 9.385v-3.27q0-.666.475-1.14t1.14-.475h8.077q.344 0 .576.232t.232.576v4.884q0 .343-.232.576t-.576.232zm0-1H12V5.5H4.116q-.27 0-.443.173t-.173.443v3.269q0 .269.173.442t.443.173m0 9.5q-.667 0-1.141-.475t-.475-1.14v-3.27q0-.666.475-1.14T4.115 13h10.077q.344 0 .576.232t.232.576v4.884q0 .344-.232.576t-.576.232zm0-1H14V14H4.116q-.27 0-.443.173t-.173.443v3.269q0 .269.173.442t.443.173M17 11h-1.192q-.343 0-.576-.232T15 10.192V5.308q0-.343.232-.576t.576-.232h4.275q.426 0 .67.351q.243.351.082.755l-1.566 4.01h.739q.434 0 .67.366q.238.366.076.77l-2.977 8.475q-.063.156-.19.215t-.264.027t-.23-.134t-.093-.27zM3.5 10V5.5zm0 8.5V14zM6.288 7.212Q6.075 7 5.75 7t-.537.213T5 7.75t.213.538t.537.212t.538-.213t.212-.537t-.213-.537m0 9.575q.213-.213.213-.538t-.213-.537t-.537-.213t-.537.213T5 16.25t.213.538t.537.212t.538-.213");
}

</style>
