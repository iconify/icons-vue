<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7i92o6_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:beard-oil" /></template>
<style>
.o7i92o6_z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 6.5q1 .5 1 2V9q0 .603-.161 1.044q.776.311 1.416.951Q14.25 12.24 14.25 14v4q0 1.76-1.245 3.005T10 22.25H6.5q-1.76 0-3.005-1.245T2.25 18v-4q0-1.76 1.245-3.005q.64-.64 1.416-.951Q4.75 9.603 4.75 9v-.5q0-1.5 1-2v-2q0-2.5 2.5-2.5t2.5 2.5zm-1.5-.25V4.5q0-1-1-1t-1 1v1.75zm10.344 2.293Q22.25 11.995 22.25 14q0 3.25-3.25 3.25T15.75 14q0-2.005 2.656-5.457q.09-.119.22-.193q.129-.074.277-.094q.148-.019.292.02t.262.13q.078.059.137.137");
}

</style>
