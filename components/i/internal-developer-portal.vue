<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey8poo3qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:internal-developer-portal" /></template>
<style>
.ey8poo3qp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 2.25h-11q-1.76 0-3.005 1.245T2.25 6.5V13q0 1.76 1.245 3.005T6.5 17.25h11q1.76 0 3.005-1.245T21.75 13V6.5q0-1.76-1.245-3.005T17.5 2.25m-6.25 5Q11.25 9.5 9 9.5T6.75 7.25T9 5t2.25 2.25M15 5q2.25 0 2.25 2.25T15 9.5t-2.25-2.25T15 5m-3.75 7.5q0 .932-.659 1.591T9 14.75t-1.591-.659T6.75 12.5q0-2.25 2.25-2.25t2.25 2.25M15 10.25q2.25 0 2.25 2.25q0 .932-.659 1.591T15 14.75t-1.591-.659t-.659-1.591q0-2.25 2.25-2.25m-12.5 9h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 20t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
