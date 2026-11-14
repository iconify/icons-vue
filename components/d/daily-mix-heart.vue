<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2_dyxpri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:daily-mix-heart" /></template>
<style>
.q2_dyxpri {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.55 21.1Q2.25 14.125 2.25 9q0-2.498 1.657-4.155Q5.502 3.25 7.75 3.25q2.699 0 4.25 2.068q1.551-2.068 4.25-2.068q2.248 0 3.843 1.595Q21.75 6.502 21.75 9q0 5.125-9.3 12.1q-.048.036-.102.064t-.111.048q-.057.019-.117.028t-.12.01q-.06 0-.12-.01q-.06-.009-.117-.028t-.111-.048q-.054-.028-.102-.064m2.2-7.1V9.25q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T13 8.5t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.654q-.531-.154-1.25-.154q-2.75 0-2.75 2.25T11 16.25T13.75 14");
}

</style>
