<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggg3ywqpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloakroom-hanger" /></template>
<style>
.ggg3ywqpo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 7q0-3 3-3t3 3q0 2.598-2.25 2.946v.687l8.71 6.775q.037.029.07.062q.883.882.516 1.615q-.332.665-1.546.665h-17q-1.214 0-1.546-.665q-.367-.733.516-1.615q.033-.033.07-.062l8.71-6.775V9.25q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 8.5q1.5 0 1.5-1.5T12 5.5T10.5 7q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9 7");
}

</style>
