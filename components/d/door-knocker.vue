<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xon9qab7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:door-knocker" /></template>
<style>
.xon9qab7z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 1.75h7q1.76 0 3.005 1.245T19.75 6v12q0 1.76-1.245 3.005T15.5 22.25h-7q-1.76 0-3.005-1.245T4.25 18V6q0-1.76 1.245-3.005T8.5 1.75m2.75 5.054q-1.491.219-2.609 1.337Q7.25 9.532 7.25 11.5t1.391 3.359T12 16.25t3.359-1.391T16.75 11.5t-1.391-3.359q-1.118-1.118-2.609-1.337V5.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 4.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146z");
}

</style>
