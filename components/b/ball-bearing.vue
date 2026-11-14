<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryzdgg5pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-bearing" /></template>
<style>
.ryzdgg5pk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75q-3.75 0-3.75 3.75T12 9.25t3.75-3.75T12 1.75q4.246 0 7.248 3.002T22.25 12q0 2.188-.797 4.046q.047-.374.047-.796q0-3.75-3.75-3.75T14 15.25T17.75 19q1.289 0 2.135-.443q-.299.353-.637.691Q16.246 22.25 12 22.25t-7.248-3.002q-.338-.338-.637-.691Q4.961 19 6.25 19Q10 19 10 15.25T6.25 11.5T2.5 15.25q0 .422.047.796Q1.75 14.188 1.75 12");
}

</style>
