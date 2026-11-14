<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwpkg0bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:budget-bar" /></template>
<style>
.qwpkg0bew {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 21V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q3.574 2.25 3.5 2.25t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.75 2.926 2.75 3v18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T4.25 21m4-17.75h10.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732H8.25q-1.036 0-1.768-.732T5.75 5.75q0-2.5 2.5-2.5m5.5 6.25h-5.5q-2.5 0-2.5 2.5q0 1.036.732 1.768t1.768.732h5.5q1.036 0 1.768-.732T16.25 12t-.732-1.768T13.75 9.5m-5.5 6.25h8.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-8.5q-2.5 0-2.5-2.5t2.5-2.5");
}

</style>
