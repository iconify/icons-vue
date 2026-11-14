<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1ywlh-7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloven-hoof-print" /></template>
<style>
.p1ywlh-7w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 2.75q-.047 0-.093.006q-3.237.404-5.073 3.963Q3.75 9.787 3.75 14q0 3.14 1.415 5.178Q6.604 21.25 8.75 21.25q2.5 0 2.5-3.25V3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014m3.093.006q3.237.404 5.073 3.963Q20.25 9.787 20.25 14q0 3.14-1.415 5.178q-1.439 2.072-3.585 2.072q-2.5 0-2.5-3.25V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014q.047 0 .093.006");
}

</style>
