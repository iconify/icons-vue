<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc0hvbynl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flower-spike" /></template>
<style>
.jc0hvbynl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 4.25q0-2.5 2-2.5t2 2.5q0 1.976-1.25 2.39v4.396l.525-.262q.226-2.024 2.475-2.024q2.5 0 2.5 2.5t-2.5 2.5q-1.851 0-2.332-1.371l-.668.335v4.822l.525-.262q.226-2.024 2.475-2.024q2.5 0 2.5 2.5t-2.5 2.5q-1.851 0-2.332-1.371l-.668.335V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-5.536l-.668-.335Q10.101 17 8.25 17q-2.5 0-2.5-2.5t2.5-2.5q2.249 0 2.475 2.024l.525.262V9.464l-.668-.335Q10.101 10.5 8.25 10.5q-2.5 0-2.5-2.5t2.5-2.5q2.249 0 2.475 2.024l.525.262V6.64Q10 6.226 10 4.25");
}

</style>
