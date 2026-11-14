<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuz4ub-oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:competitor" /></template>
<style>
.xuz4ub-oq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 8.25q0-1.864 1.318-3.182T9 3.75t3.182 1.318T13.5 8.25t-1.318 3.182T9 12.75t-3.182-1.318T4.5 8.25M18.5 4q-3.75 0-3.75 3.75t3.75 3.75t3.75-3.75T18.5 4m3.75 15.5q0-4.565-4.603-5.485q-.072-.015-.146-.015t-.147.014q-.072.015-.14.043t-.13.069t-.114.093t-.093.114t-.07.129q-.028.068-.042.141t-.015.146t.014.147q.015.072.043.14t.069.13t.093.114t.114.093q.061.041.129.07q.068.028.141.042q3.397.68 3.397 4.015q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146M3.963 15.985Q1.75 17.573 1.75 20q0 1.75 1.75 1.75h11q1.75 0 1.75-1.75q0-2.427-2.213-4.015Q11.97 14.5 9 14.5t-5.037 1.485");
}

</style>
