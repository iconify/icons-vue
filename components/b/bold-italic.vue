<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miwjtx2xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bold-italic" /></template>
<style>
.miwjtx2xn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 3.75h-6q-.065 0-.128.011q-.064.011-.124.033q-.061.022-.117.053q-.057.032-.106.073q-.05.041-.093.09t-.075.104q-.033.055-.056.115q-.024.061-.036.124l-1.5 7.5l-1.5 7.5q-.015.073-.015.147t.014.146t.043.141q.028.068.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q.038 0 .075-.004q3.494-.351 4.183-3.794q.563-2.814-1.397-4.442q1.475-.949 1.897-3.058q.689-3.444-2.402-5.112q-.167-.09-.356-.09m-6.885 9h6.188q1.937 1.142 1.484 3.407q-.468 2.339-2.826 2.593H6.415zm5.346-1.5H7.915l1.2-6h5.188q1.937 1.142 1.484 3.407q-.468 2.339-2.826 2.593");
}

</style>
