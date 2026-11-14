<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0kb_zbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ai-thumbs-up" /></template>
<style>
.l0kb_zbxb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.808 10.212l2.5-6q.042-.103.113-.189q.071-.085.163-.147t.199-.094T12 3.75q1.563 0 2.35 1.05q.817 1.089.385 2.852l-.35 2.098H18.5q1.302 0 2.032.949q.706.918.455 2.188l-.998 5.742l-.011.053Q19.398 21 17.25 21H9.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V10.5q0-.15.058-.288M7.75 12.25q0-2.5-2.5-2.5t-2.5 2.5v6q0 2.5 2.5 2.5t2.5-2.5z");
}

</style>
