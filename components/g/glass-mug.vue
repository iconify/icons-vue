<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nue0ommhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:glass-mug" /></template>
<style>
.nue0ommhs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 2.75h10q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.75h2.25q2.75 0 2.75 2.75v5.5q0 2.75-2.75 2.75h-2.25V19q0 2.75-2.75 2.75h-6q-2.75 0-2.75-2.75V9q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h10q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T15.25 9v5.75h2.25q1.25 0 1.25-1.25V8q0-1.25-1.25-1.25h-2.25V9q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-10q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q3.75 8.926 3.75 9V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
