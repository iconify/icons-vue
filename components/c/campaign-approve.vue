<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysusiac_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:campaign-approve" /></template>
<style>
.ysusiac_y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 1.75h-3.5q-2.092 0-2.433 1.75H7q-3.25 0-3.25 3.25V19q0 1.346.952 2.298T7 22.25h10q3.25 0 3.25-3.25V6.75q0-3.25-3.25-3.25h-.858q-.173-.566-.624-1.018q-.732-.732-1.768-.732M16.142 5H17q1.75 0 1.75 1.75V19q0 1.75-1.75 1.75H7q-.725 0-1.237-.513Q5.25 19.725 5.25 19V6.75Q5.25 5 7 5h.858q.173.566.624 1.018q.732.732 1.768.732h3.5q1.036 0 1.768-.732q.451-.452.624-1.018M11 14.939L9.03 12.97q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.106.105-.163.243t-.057.287t.057.287t.163.243l2.5 2.5q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l4.5-4.5q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094z");
}

</style>
