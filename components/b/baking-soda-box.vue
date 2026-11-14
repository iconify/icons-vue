<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpe-37bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baking-soda-box" /></template>
<style>
.dpe-37bjp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 1.75h5q1.76 0 3.005 1.245T18.75 6v.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 5.75H6q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V6q0-1.76 1.245-3.005T9.5 1.75M5.25 6.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T6 7.25h12q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V18q0 1.76-1.245 3.005T14.5 22.25h-5q-1.76 0-3.005-1.245T5.25 18zm3 7.5q0 3.75 3.75 3.75T15.75 14T12 10.25T8.25 14");
}

</style>
