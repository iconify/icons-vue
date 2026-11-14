<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4_duxbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:button-b" /></template>
<style>
.x4_duxbjc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M9.5 11.25v-4h2.75q2 0 2 2t-2 2zm0 1.5v4h3.25q2 0 2-2t-2-2zm5.457-.961q1.293.834 1.293 2.961q0 3.5-3.5 3.5h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8 17.5v-11q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3.5q3.5 0 3.5 3.5q0 1.666-.793 2.539");
}

</style>
