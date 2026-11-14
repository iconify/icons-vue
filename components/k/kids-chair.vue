<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe2x57mjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kids-chair" /></template>
<style>
.oe2x57mjr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 9v3.75q-1.036 0-1.768.732T2.75 15.25q0 2.5 2.5 2.5h.5V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T7.25 21v-3.25h9.5V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.25h.5q2.5 0 2.5-2.5t-2.5-2.5V9q0-2.796-1.977-4.773T12 2.25T7.227 4.227T5.25 9m1.5 0v3.75h10.5V9q0-2.175-1.538-3.712Q14.175 3.75 12 3.75T8.288 5.288Q6.75 6.825 6.75 9");
}

</style>
