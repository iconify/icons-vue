<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tan3tcc4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coker-drum" /></template>
<style>
.tan3tcc4i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 6.5q0-1.84 1.784-3.089Q9.693 2.25 12 2.25t3.966 1.161Q17.75 4.66 17.75 6.5V16q0 1.687-1.5 2.878V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-1.75q-1.235.5-2.75.5t-2.75-.5v1.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-2.622Q6.25 17.687 6.25 16z");
}

</style>
