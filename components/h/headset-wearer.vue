<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lirpbzaij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:headset-wearer" /></template>
<style>
.lirpbzaij {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3Q9.319 3 7.638 5H7Q3.25 5 3.25 8.75T7 12.5h.638q1.681 2 4.362 2t4.362-2H17q3.75 0 3.75-3.75T17 5h-.638Q14.681 3 12 3m0 1.5q-1.152 0-2.055.5h4.11q-.903-.5-2.055-.5m2.055 8q-.903.5-2.055.5t-2.055-.5zM3.75 21q0-4.75 8.25-4.75T20.25 21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T18.75 21q0-3.25-6.75-3.25T5.25 21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.75 21");
}

</style>
