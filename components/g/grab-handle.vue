<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4bln9u-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:grab-handle" /></template>
<style>
.c4bln9u-v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 3.25h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-7V8.5q0 .136-.048.264q-.048.127-.138.23l-.821.939q1.443.372 2.573 1.501q1.684 1.684 1.684 4.066t-1.684 4.066T12 21.25t-4.066-1.684T6.25 15.5t1.684-4.066q1.13-1.129 2.573-1.501l-.821-.939q-.09-.103-.138-.23Q9.5 8.636 9.5 8.5V4.75h-7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 4.074 1.75 4t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014M13 4.75h-2v3.468l1 1.143l1-1.143z");
}

</style>
