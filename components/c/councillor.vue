<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smwmiobqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:councillor" /></template>
<style>
.smwmiobqb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 6.5q0-1.864 1.318-3.182T12 2t3.182 1.318T16.5 6.5t-1.318 3.182T12 11T8.818 9.682T7.5 6.5m-1.28 8.595Q3.75 17.564 3.75 21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.314 2.03-5.345Q9.186 14.25 12 14.25t4.72 1.905q2.03 2.031 2.03 5.345q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.936-2.47-6.405Q15.436 12.75 12 12.75t-5.78 2.345m6.28 3.655q0-2.25 2.25-2.25T17 18.75T14.75 21t-2.25-2.25");
}

</style>
