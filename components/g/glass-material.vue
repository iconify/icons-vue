<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq2ysabok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:glass-material" /></template>
<style>
.lq2ysabok {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.75h10q1.76 0 3.005 1.245T21.25 7v10q0 1.76-1.245 3.005T17 21.25H7q-1.76 0-3.005-1.245T2.75 17V7q0-1.76 1.245-3.005T7 2.75m-.53 7.72q-.106.105-.163.243T6.25 11t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l4-4q.053-.052.094-.113t.069-.13t.043-.141T11.75 7t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.105-.106-.243-.163T11 6.25t-.287.057t-.243.163zm8.5-4l-8.5 8.5q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.105.106.243.163T7 16.25t.287-.057t.243-.163l8.5-8.5q.106-.105.163-.243T16.25 7t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094");
}

</style>
