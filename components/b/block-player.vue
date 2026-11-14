<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c621nqltr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:block-player" /></template>
<style>
.c621nqltr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.859 10.359q-.171.171-.351.321L6.82 3.992q.15-.18.321-.351Q8.532 2.25 10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359M4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m4.463 8.351L6.179 9.007q.344.733.962 1.352q.619.618 1.352.962m9.64 9.64l-7.711-7.711q-3.41.019-5.704 1.673Q2.25 16.702 2.25 19.5q0 1.75 1.75 1.75h13q.711 0 1.133-.289");
}

</style>
