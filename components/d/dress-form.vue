<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy5d0qq5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dress-form" /></template>
<style>
.yy5d0qq5i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 4.5q0-2.75 5.75-2.75t5.75 2.75q0 1.611-1.291 3.83q-.709 1.218-.709 1.67q0 .504.577 1.554q.923 1.682.923 2.946q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3.75v3.022q4 .246 4 3.228q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-2.982 4-3.228V15.25H7.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-1.264.923-2.946q.577-1.05.577-1.554q0-.452-.709-1.67Q6.25 6.111 6.25 4.5");
}

</style>
