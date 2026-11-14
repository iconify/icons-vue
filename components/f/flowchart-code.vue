<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr58u3bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flowchart-code" /></template>
<style>
.vr58u3bwc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 1.75h3.5q3 0 3 3t-3 3h-1v3.5h1.493q.161-.465.538-.841l1.128-1.128q.659-.66 1.591-.66t1.591.66l1.128 1.128q.377.376.538.841H17.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v4.25h1q3 0 3 3t-3 3h-3.5q-3 0-3-3t3-3h1v-3.5h-1.493q-.161.465-.538.841l-1.128 1.128q-.659.66-1.591.66t-1.591-.66l-1.128-1.128q-.377-.376-.538-.841H6.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.75 12V7.75h-1q-3 0-3-3q0-1.243.879-2.121q.878-.879 2.121-.879");
}

</style>
