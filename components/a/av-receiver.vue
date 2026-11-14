<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bykln3m6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:av-receiver" /></template>
<style>
.bykln3m6h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 4.25H6q-1.76 0-3.005 1.245T1.75 8.5v5q0 1.76 1.245 3.005q.573.573 1.255.882V19.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1.756q.124.006.25.006h12q.126 0 .25-.006V19.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.113q.682-.309 1.255-.882Q22.25 15.26 22.25 13.5v-5q0-1.76-1.245-3.005T18 4.25M11.5 8h1q1.036 0 1.768.732T15 10.5v1q0 1.036-.732 1.768T12.5 14h-1Q9 14 9 11.5v-1Q9 8 11.5 8M6 9q2 0 2 2t-2 2t-2-2t2-2m10 2q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
