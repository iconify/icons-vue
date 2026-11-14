<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f35876j5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:assets-column" /></template>
<style>
.f35876j5n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 2.25h-1.5q-2.5 0-2.5 2.5v14.5q0 .541.2 1H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T2.25 21t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h18q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 20.25h-1.45q.2-.459.2-1v-7.5q0-2.5-2.5-2.5h-1.5q-2.5 0-2.5 2.5v7.5q0 .541.2 1h-1.9q.2-.459.2-1V4.75q0-1.036-.732-1.768T9.25 2.25");
}

</style>
