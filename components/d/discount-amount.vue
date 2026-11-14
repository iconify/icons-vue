<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg4khdc3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:discount-amount" /></template>
<style>
.eg4khdc3d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 1.75h4.788q1.398 0 2.386.989l7.625 7.625q2.386 2.386 0 4.772l-4.788 4.788q-2.386 2.386-4.772 0l-7.625-7.625q-.989-.988-.989-2.386V5.125q0-3.375 3.375-3.375M6.75 4.5Q4.5 4.5 4.5 6.75T6.75 9T9 6.75T6.75 4.5m8.75 8.25H10q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
