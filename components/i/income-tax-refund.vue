<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6dojo4mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:income-tax-refund" /></template>
<style>
.y6dojo4mi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.75H6q-1.76 0-3.005 1.245T1.75 7v3.5q0 1.76 1.245 3.005T6 14.75h10.25v2.75q0 1.5-1.5 1.5H9.061l.969-.97q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.105-.106-.243-.163T9.5 16.75t-.287.057t-.243.163l-2.25 2.25q-.106.105-.163.243t-.057.287t.057.287t.163.243l2.25 2.25q.105.106.243.163t.287.057t.287-.057t.243-.163q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-.969-.97h5.689q3 0 3-3v-2.75H18q1.76 0 3.005-1.245T22.25 10.5V7q0-1.76-1.245-3.005T18 2.75m-9.25 6Q8.75 5.5 12 5.5t3.25 3.25T12 12T8.75 8.75");
}

</style>
