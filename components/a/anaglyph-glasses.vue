<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6tp5hbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anaglyph-glasses" /></template>
<style>
.l6tp5hbga {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 8.25h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.035Q21.75 11.109 21.75 13q0 1.968-1.391 3.359T17 17.75t-3.359-1.391T12.25 13q0-1.891 1.285-3.25h-3.07Q11.75 11.109 11.75 13q0 1.968-1.391 3.359T7 17.75t-3.359-1.391T2.25 13q0-1.891 1.285-3.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 9.074 1.75 9t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
