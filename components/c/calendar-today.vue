<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9nyspbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:calendar-today" /></template>
<style>
.p9nyspbgu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 3.75V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q8.074 1.75 8 1.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v1.251q-2.042.043-3.499 1.5Q2.25 6.752 2.25 8.875v7.75q0 2.123 1.501 3.624t3.624 1.501h9.25q2.123 0 3.624-1.501t1.501-3.624v-7.75q0-2.123-1.501-3.624q-1.457-1.457-3.499-1.5V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v1.25zm.5 11.5q0-2.75 2.75-2.75t2.75 2.75T12 18t-2.75-2.75");
}

</style>
