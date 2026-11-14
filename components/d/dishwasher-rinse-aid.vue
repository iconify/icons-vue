<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftfcfsuts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dishwasher-rinse-aid" /></template>
<style>
.ftfcfsuts {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 1.75h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3.155L5.512 8.431q-.125.106-.193.256q-.069.149-.069.313v10.5q0 2.75 2.75 2.75h8q2.75 0 2.75-2.75V9q0-.164-.069-.313q-.068-.15-.193-.256L15.25 5.655V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014m-1.924 9.27Q15.25 14.228 15.25 16q0 3.25-3.25 3.25T8.75 16q0-1.772 2.674-4.98q.047-.057.105-.103q.057-.047.122-.081q.066-.034.137-.055t.144-.028t.147.001t.144.03t.136.057q.064.036.121.083q.053.043.096.096");
}

</style>
