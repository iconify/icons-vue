<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj6lzvb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bivouac" /></template>
<style>
.pj6lzvb2u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 17.5v-3q0-2.75 2.75-2.75h5.325q.363-2.506 2.104-4.066q1.858-1.666 4.311-1.495q6.01.42 6.01 8.311v3q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m12-.75h4v-1.5q0-2-2-2t-2 2zm5.5 0h1.5V14.5q0-6.492-4.615-6.814q-1.819-.127-3.205 1.115q-1.523 1.365-1.682 3.749q-.004.07-.022.139q-.018.068-.048.132t-.072.121t-.094.106t-.111.086t-.126.064q-.065.026-.135.039q-.069.013-.14.013h-6q-1.25 0-1.25 1.25v2.25h9v-1.5q0-3.5 3.5-3.5t3.5 3.5z");
}

</style>
