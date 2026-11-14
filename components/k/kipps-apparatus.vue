<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkjhq5bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kipps-apparatus" /></template>
<style>
.qkjhq5bfj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.25 7.19q2-.345 2-2.69q0-2.75-2.75-2.75T8.75 4.5q0 2.345 2 2.69v1.102q-3 .354-3 3.708q0 2.542 1.723 3.361q-4.223.512-4.223 3.389q0 3.5 6.25 3.5t6.25-3.5q0-2.877-4.223-3.389q1.455-.691 1.681-2.611h3.042v.75q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 9.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v.75h-3.042q-.312-2.646-2.958-2.958zm1.5 4.81q0 2.25-2.25 2.25T9.25 12t2.25-2.25T13.75 12m-1-7.5q0 1.25-1.25 1.25T10.25 4.5t1.25-1.25t1.25 1.25m-6 14.25q0-2 4.75-2t4.75 2t-4.75 2t-4.75-2");
}

</style>
