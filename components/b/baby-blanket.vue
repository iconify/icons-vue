<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t20mjqitc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-blanket" /></template>
<style>
.t20mjqitc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.998 4.439q-2.748-2.442-5.496 0q-.12.107-.186.254q-.066.146-.066.307v14q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75V5q0-.138-.049-.267q-.049-.128-.14-.231q-.1-.112-.234-.177t-.283-.074q-.149-.008-.29.04q-.141.049-.252.148q-1.752 1.558-3.504 0q-2.748-2.442-5.496 0q-1.752 1.558-3.504 0M21.75 13q0 .149-.057.287t-.163.243l-8 8q-.105.106-.243.163T13 21.75t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T12.25 21t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l8-8q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287");
}

</style>
