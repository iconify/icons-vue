<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6c6g2bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:frac-sand" /></template>
<style>
.u6c6g2bci {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 6.5q0-2.25 2.25-2.25t2.25 2.25t-2.25 2.25t-2.25-2.25M18.5 10Q16 10 16 12.5t2.5 2.5q1.036 0 1.768-.732T21 12.5t-.732-1.768T18.5 10m-16 7.75h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-6.423q-1.694-6-6.077-6t-6.077 6H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T1.75 17t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014m6.5-6q3.108 0 4.512 4.5H4.488q1.404-4.5 4.512-4.5");
}

</style>
