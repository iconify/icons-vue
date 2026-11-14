<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjs-x4_5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blob" /></template>
<style>
.fjs-x4_5u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.23 4.674Q14.322 2.25 12 2.25q-2.482 0-4.031 2.756q-.594 1.058-.999 1.464q-.432.431-1.681 1.16Q2.25 9.403 2.25 11.5q0 4.311 3.22 7.53q2.719 2.72 7.53 2.72q1.551 0 4.13-2.596q1.245-1.253 1.705-1.483q1.461-.73 2.089-4.063q.608-3.221-.253-4.943q-.963-1.926-3.441-3.991m-6.22 7.076q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H11q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
