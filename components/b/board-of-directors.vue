<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzu2rvbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:board-of-directors" /></template>
<style>
.bzu2rvbib {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25q-2.25 0-2.25 2.25T6 6.75T8.25 4.5T6 2.25M9.75 4.5q0-2.25 2.25-2.25t2.25 2.25T12 6.75T9.75 4.5M18 2.25q-2.25 0-2.25 2.25T18 6.75t2.25-2.25T18 2.25M3.25 16V8q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T4 7.25h16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v8q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.25 16m.5 3.5q0-2.25 2.25-2.25t2.25 2.25T6 21.75T3.75 19.5M12 17.25q-2.25 0-2.25 2.25T12 21.75t2.25-2.25T12 17.25m3.75 2.25q0-2.25 2.25-2.25t2.25 2.25T18 21.75t-2.25-2.25");
}

</style>
