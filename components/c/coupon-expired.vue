<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-tgfdbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coupon-expired" /></template>
<style>
.f-tgfdbju {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 2.25h-7q-.932 0-1.591.659T2.25 4.5v7q0 .138.049.268q.05.129.142.232l8.5 9.5q.045.05.098.091q.053.042.112.073t.124.051q.064.021.13.029q.067.008.134.005q.067-.004.133-.019q.065-.015.127-.042q.061-.027.117-.064l.75-.5q.077-.051.139-.12q.063-.068.106-.15q.044-.082.066-.172T13 20.5v-5q0-1.25 1.25-1.25h2Q14 15 14 18q0 4 4 4t4-4q0-3-2.25-3.75H20q.149 0 .287-.057t.243-.163l1-1q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113l-9.5-9.5q-.105-.106-.243-.163T11.5 2.25m-6 5.5q0-2.25 2.25-2.25T10 7.75T7.75 10T5.5 7.75");
}

</style>
