<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4n19zb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loveseat" /></template>
<style>
.o4n19zb5x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 9.31V8.5q0-1.346.952-2.298T7 5.25h10q3.25 0 3.25 3.25v.81q2 .345 2 2.69v6q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 18v-6q0-2.345 2-2.69m9 3.94h4V12q0-2.345 2-2.69V8.5q0-1.75-1.75-1.75h-4.25zm-1.5-6.5v6.5h-4V12q0-2.345-2-2.69V8.5q0-.725.513-1.237Q6.275 6.75 7 6.75z");
}

</style>
