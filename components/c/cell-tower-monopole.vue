<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4bhw1bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cell-tower-monopole" /></template>
<style>
.o4bhw1bui {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q2.25 0 2.25 2.25v3.5q0 1.776-1.402 2.15l1.554 11.1H16.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.098l1.554-11.1Q9.75 9.276 9.75 7.5V4q0-2.25 2.25-2.25M7.841 3.409Q7.182 2.75 6.25 2.75Q4 2.75 4 5v2q0 2.25 2.25 2.25q.932 0 1.591-.659T8.5 7V5q0-.932-.659-1.591m9.909-.659Q20 2.75 20 5v2q0 2.25-2.25 2.25T15.5 7V5q0-2.25 2.25-2.25m-4.862 18L12 14.409l-.888 6.341z");
}

</style>
