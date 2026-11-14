<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufp-lybaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coffee-machine-room" /></template>
<style>
.ufp-lybaw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.25 2.25H5.75q-2.5 0-2.5 2.5v14.5q0 1.036.732 1.768t1.768.732H18.5q2.25 0 2.25-2.25q0-1.5-1-2V16q0-.154-.061-.295l-1.439-3.359V11q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v1.346l-1.439 3.359q-.061.141-.061.295v1.25h-.5q-1 0-1-1v-6.5q0-1 1-1h8.5q2.5 0 2.5-2.5v-1.5q0-2.5-2.5-2.5");
}

</style>
