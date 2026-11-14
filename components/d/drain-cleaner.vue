<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoqcisvox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drain-cleaner" /></template>
<style>
.yoqcisvox {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 1.75h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3.155L5.512 8.431q-.125.106-.193.256q-.069.149-.069.313v10.5q0 2.75 2.75 2.75h8q2.75 0 2.75-2.75V9q0-.164-.069-.313q-.068-.15-.193-.256L15.25 5.655V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014m-3.75 9.5h2.5q1.036 0 1.768.732t.732 1.768v1.5q0 1.036-.732 1.768t-1.768.732h-2.5q-2.5 0-2.5-2.5v-1.5q0-2.5 2.5-2.5");
}

</style>
