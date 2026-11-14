<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqzblk3of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:focus-group" /></template>
<style>
.tqzblk3of {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 1.75h13q1.346 0 2.298.952T21.75 5v10q0 1.346-.952 2.298t-2.298.952h-7.718l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.75H5.5q-3.25 0-3.25-3.25V5q0-1.346.952-2.298T5.5 1.75m6.5 3q-2.75 0-2.75 2.75T12 10.25t2.75-2.75T12 4.75m0 6.75q-5 0-5 3.25q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146Q8.5 13 12 13t3.5 1.75q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.25-5-3.25");
}

</style>
