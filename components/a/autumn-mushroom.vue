<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-qhfuksb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:autumn-mushroom" /></template>
<style>
.i-qhfuksb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.739 6.412Q1.75 9.558 1.75 14q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6V19q0 2.75 2.75 2.75h1.5q2.75 0 2.75-2.75v-4.25h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-4.442-2.989-7.588Q16.257 3.25 12 3.25T4.739 6.412M12.25 9.5q0-2.25 2.25-2.25t2.25 2.25t-2.25 2.25t-2.25-2.25m-3.75-2q2.25 0 2.25 2.25T8.5 12T6.25 9.75T8.5 7.5M10 19v-4.25h4V19q0 1.25-1.25 1.25h-1.5Q10 20.25 10 19");
}

</style>
