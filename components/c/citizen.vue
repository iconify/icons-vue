<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on01k6bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:citizen" /></template>
<style>
.on01k6bds {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.75h12q1.76 0 3.005 1.245T22.25 7v9q0 1.76-1.245 3.005T18 20.25h-1q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-5.25-5.75-5.25T6.25 19.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H6q-1.76 0-3.005-1.245T1.75 16V7q0-1.76 1.245-3.005T6 2.75m1 17.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.75 4.25-3.75t4.25 3.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014zM12 6Q8.5 6 8.5 9.5T12 13t3.5-3.5T12 6");
}

</style>
