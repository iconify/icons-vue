<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifurec0mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:conduit" /></template>
<style>
.ifurec0mi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 2.75h4.5Q22 2.75 22 5v.5q0 .932-.659 1.591q-.272.272-.591.432V12.5q0 3.624-2.563 6.187T12 21.25H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 14.75h9q.932 0 1.591-.659t.659-1.591V7.523q-.319-.16-.591-.432Q13 6.432 13 5.5V5q0-2.25 2.25-2.25m.5 5v4.75q0 1.553-1.098 2.652Q13.553 16.25 12 16.25H3.75v3.5H12q3.003 0 5.127-2.123T19.25 12.5V7.75z");
}

</style>
