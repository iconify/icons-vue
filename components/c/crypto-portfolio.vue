<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-yh9cu8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crypto-portfolio" /></template>
<style>
.s-yh9cu8y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.75 11.75v7q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T11 19.5q-3.521 0-6.01-2.49Q2.5 14.521 2.5 11t2.49-6.01Q7.479 2.5 11 2.5t6.01 2.49Q19.5 7.479 19.5 11q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014zm2 1.25h7.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 3.521-2.49 6.01q-2.489 2.49-6.01 2.49q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13 21.5v-7.75q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
