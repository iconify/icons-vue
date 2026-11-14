<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cazdglbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gpu-fans" /></template>
<style>
.cazdglbqe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 4.75H6q-1.76 0-3.005 1.245T1.75 9v4q0 1.76 1.245 3.005q.971.971 2.255 1.185v2.31q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.25H18q1.76 0 3.005-1.245T22.25 13V9q0-1.76-1.245-3.005T18 4.75M4.5 11q0-3.5 3.5-3.5t3.5 3.5T8 14.5q-1.75 0-2.625-.875T4.5 11M16 7.5q3.5 0 3.5 3.5T16 14.5T12.5 11T16 7.5M6 11q0-2 2-2t2 2t-2 2t-2-2m10 2q-2 0-2-2t2-2t2 2t-2 2m-9.25 5.75v-1.5h5.5v1.5z");
}

</style>
