<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4hjj1bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blocking-marks" /></template>
<style>
.d4hjj1bxr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.793 4.75h11.338q1.262 0 2.011 1.015t.378 2.221l-2.923 9.5q-.544 1.765-2.39 1.764H4.869q-1.262 0-2.011-1.015t-.378-2.221l2.923-9.5q.544-1.764 2.39-1.764M12.5 8.5h-4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T8.5 10h3.069l-1.052 4.841q-.016.072-.017.146t.012.146q.013.073.04.142t.067.131t.091.115t.112.095t.129.072t.14.045t.146.017t.146-.012t.142-.04t.131-.067t.115-.091t.095-.112t.072-.129q.029-.067.045-.14L13.104 10H16.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16.5 8.5z");
}

</style>
