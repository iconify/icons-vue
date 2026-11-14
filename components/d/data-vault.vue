<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o24tr-brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-vault" /></template>
<style>
.o24tr-brr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.494 6.575q.43-.58.965-1.116Q9.169 2.75 13 2.75t6.541 2.709Q22.25 8.169 22.25 12t-2.709 6.541Q16.831 21.25 13 21.25t-6.541-2.709q-.535-.536-.965-1.116q-.46.825-1.744.825q-2 0-2-2v-.5q0-.828.586-1.414t1.414-.586q.078 0 .152.003Q3.75 12.908 3.75 12t.152-1.753q-.074.003-.152.003q-2 0-2-2v-.5q0-2 2-2q1.284 0 1.744.825M7.75 12q-.001 2.175 1.537 3.713T13 17.252t3.713-1.539T18.25 12q.001-2.175-1.537-3.713T13 6.748T9.287 8.287T7.75 12");
}

</style>
