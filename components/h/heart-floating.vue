<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-ogk1bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-floating" /></template>
<style>
.a-ogk1bcv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 4q0-1.75 1.75-1.75q.604 0 1 .209q.396-.209 1-.209q1.75 0 1.75 1.75q0 .149-.057.287t-.163.243l-2 2q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-2-2q-.106-.105-.163-.243T16.75 4M12 7.25q-2.25 0-2.25 2.25q0 .149.057.287t.163.243l3 3q.105.106.243.163t.287.057t.287-.057t.243-.163l3-3q.106-.105.163-.243t.057-.287q0-2.25-2.25-2.25q-.951 0-1.5.402q-.549-.402-1.5-.402M1.97 16.03q-.106-.105-.163-.243T1.75 15.5q0-3 3-3q1.5 0 2.25.75q.75-.75 2.25-.75q3 0 3 3q0 .149-.057.287t-.163.243l-4.5 4.5q-.052.053-.113.094t-.13.069t-.141.043T7 20.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094z");
}

</style>
