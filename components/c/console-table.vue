<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awj_8pfmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:console-table" /></template>
<style>
.awj_8pfmy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 3.75H4.25q-2 0-2 2t2 2h.5V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-5.25h11.5v5.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V7.75h.5q.828 0 1.414-.586t.586-1.414t-.586-1.414t-1.414-.586m-2 10H6.25v-6h11.5z");
}

</style>
