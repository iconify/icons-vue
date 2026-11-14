<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6u57jbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ear-tag" /></template>
<style>
.n6u57jbvf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 8.31V9q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T12.75 9v-.69q2 .345 2 2.69q0 2.75-2.75 2.75T9.25 11q0-2.345 2-2.69m0-2.023q-2.317.234-4.023 1.94Q5.25 10.204 5.25 13v6q0 1.346.952 2.298t2.298.952h7q1.346 0 2.298-.952T18.75 19v-6q0-2.796-1.977-4.773l-.023-.023V4.5q0-2.75-2.75-2.75T11.25 4.5zm1.5 0V4.5q0-1.25 1.25-1.25t1.25 1.25v2.563q-1.146-.639-2.5-.776");
}

</style>
