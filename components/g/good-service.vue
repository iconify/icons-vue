<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2eq0pbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:good-service" /></template>
<style>
.s2eq0pbgy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 13.939L5.03 9.47q-.052-.053-.113-.094t-.13-.069t-.141-.043T4.5 9.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T3.75 10t.057.287t.163.243l5 5q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l10-10q.106-.105.163-.243T20.25 5t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094zm-6 2.311q-2.25 0-2.25 2.25t2.25 2.25q1.837 0 2.174-1.5h12.652q.337 1.5 2.174 1.5q2.25 0 2.25-2.25t-2.25-2.25q-1.837 0-2.174 1.5H5.674q-.337-1.5-2.174-1.5");
}

</style>
