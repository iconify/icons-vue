<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pddwo-b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:break-room" /></template>
<style>
.pddwo-b_q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 9v1.523q-2 .738-2 3.477q0 3.062 2.5 3.624V19.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1.75h11.5v1.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1.876q2.5-.562 2.5-3.624q0-2.739-2-3.477V9q0-2.75-2.75-2.75H7Q4.25 6.25 4.25 9M6 10.25q-.127 0-.25.004V9q0-1.25 1.25-1.25h10q1.25 0 1.25 1.25v1.254q-.123-.004-.25-.004z");
}

</style>
