<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zajddwshm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:community-solar" /></template>
<style>
.zajddwshm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.449 12.5H5.241q-.099 0-.198-.011q-.099-.012-.196-.034q-.096-.022-.19-.056q-.094-.033-.183-.076q-.089-.044-.173-.097t-.161-.116t-.147-.134t-.131-.149t-.113-.163t-.093-.175t-.074-.184q-.031-.095-.052-.192t-.03-.196t-.008-.198t.015-.198q.013-.099.037-.195l1.625-6.5q.035-.141.093-.274t.137-.255t.178-.229t.212-.197q.115-.089.243-.159q.127-.069.265-.117q.137-.047.28-.071t.289-.024h10.268q.145 0 .289.024q.143.024.28.071q.138.048.265.117q.128.07.243.159q.114.09.212.197t.178.229q.079.122.137.255t.093.274l1.625 6.5q.073.292.044.592t-.157.573M12 2.5v10m-7.75-5h15.5m-11.25 5v8m-3 0h6m4.5-4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

</style>
