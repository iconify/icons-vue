<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1rtcabyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:breakout-game" /></template>
<style>
.i1rtcabyi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 2.25h4.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-4.5q-2.5 0-2.5-2.5t2.5-2.5m14.5 0h-4.5q-2.5 0-2.5 2.5t2.5 2.5h4.5q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732M9.75 8.5h4.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-4.5q-1.036 0-1.768-.732T7.25 11q0-2.5 2.5-2.5m9.5 5q-2.5 0-2.5 2.5t2.5 2.5t2.5-2.5t-2.5-2.5M5 19.75h8q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5 19.75");
}

</style>
