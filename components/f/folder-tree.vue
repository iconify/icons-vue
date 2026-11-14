<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5yqud2_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:folder-tree" /></template>
<style>
.j5yqud2_m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 2.25h2q3.25 0 3.25 3.25T7.5 8.75h-.25v2.5h5.549q.351-2.5 3.201-2.5h2.5q1.346 0 2.298.952T21.75 12t-.952 2.298t-2.298.952H16q-2.85 0-3.201-2.5H7.25v5.5h5.549q.351-2.5 3.201-2.5h2.5q1.346 0 2.298.952T21.75 19t-.952 2.298t-2.298.952H16q-1.346 0-2.298-.952q-.675-.675-.871-1.548H6.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.75 19V8.75H5.5q-3.25 0-3.25-3.25q0-1.346.952-2.298T5.5 2.25");
}

</style>
