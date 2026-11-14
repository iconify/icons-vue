<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txoccib-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ampoule" /></template>
<style>
.txoccib-d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 5.5V9q0 .338-.787 1.105Q7.25 11.775 7.25 13.5v6q0 2.75 2.75 2.75h4q2.75 0 2.75-2.75v-6q0-1.725-1.713-3.395Q14.25 9.338 14.25 9V5.5q0-2.401-1.834-3.624q-.092-.062-.199-.094q-.106-.032-.217-.032t-.217.032t-.199.094Q9.75 3.099 9.75 5.5m7 10q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 14.75h8q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
