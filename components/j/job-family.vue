<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg-mg3b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:job-family" /></template>
<style>
.qg-mg3b3p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75Q8.75 1.75 8.75 5q0 2.85 2.5 3.201v6.488L8.491 11.93q.259-.585.259-1.43q0-2.75-2.75-2.75T3.25 10.5T6 13.25q.845 0 1.43-.259l3.82 3.82v3.939H9q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T15 20.75h-2.25v-6.439l3.82-3.82q.585.259 1.43.259q2.75 0 2.75-2.75T18 5.25T15.25 8q0 .845.259 1.43l-2.759 2.759V8.201q2.5-.351 2.5-3.201q0-3.25-3.25-3.25");
}

</style>
