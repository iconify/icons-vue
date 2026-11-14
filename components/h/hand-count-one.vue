<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe6ngwb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hand-count-one" /></template>
<style>
.oe6ngwb2f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 12.25H6.5q-2.25 0-2.25 2.25v1q0 2.959 2.264 4.884Q8.71 22.25 12 22.25h1q3.112 0 5.164-1.885q2.086-1.917 2.086-4.865V13q0-3.25-3.25-3.25h-4.75v-5q0-2.5-2.5-2.5t-2.5 2.5zm7.5-2.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T14 13.5v-3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
