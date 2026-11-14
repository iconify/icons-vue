<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fflb61b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:curtain-rod" /></template>
<style>
.fflb61b6d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 2.75Q1.5 2.75 1.5 4.5t1.75 1.75q.604 0 1-.209V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T10 20.5q0-.086-.02-.17q-1.648-7.067 1.055-15.08h1.93q2.703 8.013 1.055 15.08q-.02.084-.02.17q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V6.041q.396.209 1 .209q1.75 0 1.75-1.75t-1.75-1.75q-1.323 0-1.646 1H4.896q-.323-1-1.646-1m2.5 2.5h3.705q-2.466 7.637-1.132 14.5H5.75zm9.927 14.5q1.334-6.863-1.132-14.5h3.705v14.5z");
}

</style>
