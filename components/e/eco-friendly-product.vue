<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooy9mlbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eco-friendly-product" /></template>
<style>
.ooy9mlbsy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 1.75H4Q1.75 1.75 1.75 4v1.5q0 .932.659 1.591q.376.376.841.538V19.5q0 1.75 1.75 1.75h14q1.75 0 1.75-1.75V7.629q.465-.162.841-.538q.659-.659.659-1.591V4q0-2.25-2.25-2.25M4.75 19.5V7.75h14.5V19.5q0 .25-.25.25H5q-.25 0-.25-.25m2.752-1q9.748-.001 9.748-8.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-9.75 0-9.75 8.5q0-.15.057-.287q.057-.138.163-.243l4.25-4.25q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-4.25 4.25q-.105.106-.242.163q-.138.057-.286.057");
}

</style>
