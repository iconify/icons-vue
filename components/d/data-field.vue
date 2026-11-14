<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy8x47blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-field" /></template>
<style>
.oy8x47blz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 2.75h-5q-1.036 0-1.768.732T1.75 5.25q0 2.5 2.5 2.5h5q2.5 0 2.5-2.5q0-1.036-.732-1.768T9.25 2.75M6 9.25h12q1.76 0 3.005 1.245T22.25 13.5v3q0 1.76-1.245 3.005T18 20.75H6q-1.76 0-3.005-1.245T1.75 16.5v-3q0-1.76 1.245-3.005T6 9.25M7.25 17v-4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5.75 13v4q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T7.25 17");
}

</style>
