<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcfsjo48x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gate-rounded" /></template>
<style>
.zcfsjo48x {
  fill: currentColor;
  d: path("M4.028 15.74q-.143-.143-.143-.355v-6.77q0-.212.144-.356t.356-.143t.356.143t.144.357v6.769q0 .212-.144.356t-.357.144t-.356-.144m15.23 0q-.142-.144-.142-.356v-6.77q0-.212.143-.356q.144-.143.357-.143t.356.143t.144.357v6.769q0 .212-.144.356t-.357.144t-.356-.144M6.423 16.766V9.462q0-1.266.893-2.153q.892-.886 2.146-.886h1.23q.344 0 .576.232t.232.576V11.5h-1.192q-.213 0-.356.144t-.144.357t.144.356t.356.143H11.5v4.27q0 .343-.232.575t-.576.232H7.231q-.343 0-.576-.234q-.232-.233-.232-.578m6.077.004V12.5h1.192q.213 0 .356-.144t.144-.357t-.144-.356t-.356-.143H12.5V7.23q0-.342.232-.575t.576-.232h1.23q1.266 0 2.153.887q.886.886.886 2.152v7.304q0 .344-.232.578t-.576.233h-3.461q-.344 0-.576-.232t-.232-.576");
}

</style>
