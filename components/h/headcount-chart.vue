<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6dq1kbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:headcount-chart" /></template>
<style>
.c6dq1kbcr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 4.5Q16.5 2 19 2t2.5 2.5T19 7t-2.5-2.5M12 5.75q-2.5 0-2.5 2.5t2.5 2.5q1.036 0 1.768-.732T14.5 8.25t-.732-1.768T12 5.75M22.75 21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H2q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T2 20.75h.25V18.5q0-2.75 2.75-2.75t2.75 2.75v2.25h1.5v-6Q9.25 12 12 12t2.75 2.75v6h1.5V11q0-2.75 2.75-2.75T21.75 11v9.75H22q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146M2.5 12q0-2.5 2.5-2.5T7.5 12T5 14.5T2.5 12m17.75 8.75V11q0-1.25-1.25-1.25T17.75 11v9.75zm-7-6v6h-2.5v-6q0-1.25 1.25-1.25t1.25 1.25m-7 6V18.5q0-1.25-1.25-1.25T3.75 18.5v2.25z");
}

</style>
