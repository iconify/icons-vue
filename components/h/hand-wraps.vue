<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9kx8w4pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hand-wraps" /></template>
<style>
.a9kx8w4pw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 9q0-3.003 2.123-5.127T10 1.75t5.127 2.123Q17.25 5.997 17.25 9v11.418l2.5-.938V12q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v8q0 .115-.034.224t-.1.203q-.065.094-.155.165q-.09.07-.198.11l-4 1.5q-.127.048-.263.048q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-8.073q-.285.361-.623.7Q13.003 16.25 10 16.25t-5.127-2.123Q2.75 12.003 2.75 9M7 9q0-3 3-3t3 3t-3 3t-3-3");
}

</style>
