<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh80v8b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:compact-tractor" /></template>
<style>
.yh80v8b5y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 15.75h-6.798q-.224-1.697-1.49-2.962Q9.675 11.25 7.5 11.25t-3.712 1.538Q2.25 14.325 2.25 16.5t1.538 3.712Q5.325 21.75 7.5 21.75t3.712-1.538q1.266-1.265 1.49-2.962h3.055q-.257.621-.257 1.5q0 3 3 3t3-3q0-1.198-.479-1.918q.729-.552.729-1.832v-2.5q0-2.25-2.25-2.25h-6.25V4.5q0-1.75-1.75-1.75H5q-1.75 0-1.75 1.75V10q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T4.75 10V4.5q0-.25.25-.25h6.5q.25 0 .25.25V11q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q.75 0 .75.75V15q0 .75-.75.75m-14.25.75q0-2.25 2.25-2.25t2.25 2.25t-2.25 2.25t-2.25-2.25");
}

</style>
