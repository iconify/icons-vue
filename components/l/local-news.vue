<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9yiskbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:local-news" /></template>
<style>
.l9yiskbsz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 21.25h14q2.75 0 2.75-2.75v-13q0-2.75-2.75-2.75H9q-2.75 0-2.75 2.75v2.75H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.25 8.926 2.25 9v9.5q0 2.75 2.75 2.75m14-1.5H7.75V5.5q0-1.25 1.25-1.25h10q1.25 0 1.25 1.25v13q0 1.25-1.25 1.25M9.75 10q0 3.811 3.72 7.53q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q3.72-3.719 3.72-7.53q-.001-1.76-1.246-3.004Q15.76 5.752 14 5.752t-3.004 1.244Q9.751 8.24 9.75 10m-6-.25h2.5v10H5q-1.25 0-1.25-1.25z");
}

</style>
