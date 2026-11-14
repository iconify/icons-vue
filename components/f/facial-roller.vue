<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntda21bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:facial-roller" /></template>
<style>
.ntda21bjw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 2.25h-6.5q-1.243 0-2.121.879q-.601.6-.791 1.371H5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V8.5q0 2.75 2.75 2.75h4.25v5h-.75q-2.75 0-2.75 2.75t2.75 2.75h3q2.75 0 2.75-2.75t-2.75-2.75h-.75v-5H17q2.75 0 2.75-2.75V5.25q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 4.5h-.838q-.19-.771-.791-1.371q-.878-.879-2.121-.879M7 9.75q-1.25 0-1.25-1.25V6h.054q.348 2.25 2.946 2.25h6.5q2.598 0 2.946-2.25h.054v2.5q0 1.25-1.25 1.25z");
}

</style>
