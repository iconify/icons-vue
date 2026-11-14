<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r17h5k4uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crank" /></template>
<style>
.r17h5k4uy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2.5q-2.75 0-2.75 2.75q0 .816.242 1.389l-2.58 2.277Q11.853 7 9 7Q5.997 7 3.873 9.123T1.75 14.25q0 3.003 2.123 5.127T9 21.5t5.127-2.123q2.123-2.124 2.123-5.127q0-2.385-1.339-4.215l2.62-2.312Q18.127 8 19 8q2.75 0 2.75-2.75T19 2.5m-9.99 11q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T9.01 15H9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 13.5z");
}

</style>
