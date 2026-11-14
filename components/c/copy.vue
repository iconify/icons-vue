<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o84ri2v2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:copy" /></template>
<style>
.o84ri2v2n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 14.5V6q0-3.25 3.25-3.25h8q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-8Q4.75 4.25 4.75 6v8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T4 15.25t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146m9.625-6.75q-2.123 0-3.624 1.501T7.75 12.875v3.25q0 2.123 1.501 3.624t3.624 1.501h3.25q2.123 0 3.624-1.501t1.501-3.624v-3.25q0-2.123-1.501-3.624T16.125 7.75z");
}

</style>
