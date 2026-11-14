<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3vft-bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coffee-mug" /></template>
<style>
.i3vft-bug {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 3.75H3.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v12q0 1.968 1.391 3.359T7.5 21.25H12q1.968 0 3.359-1.391T16.75 16.5v-1.25H17q1.76 0 3.005-1.245T21.25 11t-1.245-3.005T17 6.75h-.25V4.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 3.75m1 10h-.25v-5.5H17q2.75 0 2.75 2.75q0 1.139-.805 1.945q-.806.805-1.945.805");
}

</style>
