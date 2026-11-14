<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5jm70j6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drink-coaster" /></template>
<style>
.l5jm70j6p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.5 3.25h-8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.75 4v8.392q-4.84 1.098-4.998 3.56L1.75 16q0 1.973 3.273 3.179Q7.931 20.25 12 20.25t6.977-1.071Q22.25 17.973 22.25 16q-.008-2.874-6-3.891v-.865q2.749-.123 2.749-2.994T16.25 5.256V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014m1.999 5q0 1.368-1.249 1.488V6.762q1.249.119 1.249 1.488m-1.251 5.379q4.497.789 4.502 2.371q0 .927-2.292 1.771q-2.657.979-6.458.979t-6.458-.979q-2.263-.834-2.292-1.748q.115-1.285 3.515-2.096Q6.971 16.75 10 16.75h3q1.346 0 2.298-.952q.906-.906.95-2.169");
}

</style>
