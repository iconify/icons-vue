<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_2jfacvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:face-oil" /></template>
<style>
.s_2jfacvc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 7.5q1 .5 1 2q0 .603-.161 1.044q.776.311 1.416.951Q14.25 12.74 14.25 14.5V18q0 1.76-1.245 3.005T10 22.25H7q-1.76 0-3.005-1.245T2.75 18v-3.5q0-1.76 1.245-3.005q.64-.64 1.416-.951q-.161-.441-.161-1.044q0-1.5 1-2v-3q0-2.25 2.25-2.25t2.25 2.25zm-1.5-.25V4.5q0-.75-.75-.75t-.75.75v2.75zm9.14 4.314q.072-.102.174-.174q.06-.043.128-.074q.067-.03.139-.047q.072-.016.146-.019q.073-.002.146.01t.142.038t.132.066q.063.039.117.089q.053.051.096.111q2.64 3.696 2.64 5.936q0 3.25-3.25 3.25t-3.25-3.25q0-2.24 2.64-5.936");
}

</style>
