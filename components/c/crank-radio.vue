<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0zt_91pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crank-radio" /></template>
<style>
.w0zt_91pa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.505 8.495q-.933-.933-2.156-1.167l2.775-4.162q.041-.061.069-.13q.028-.068.043-.14t.014-.147q0-.074-.015-.146q-.014-.073-.042-.141t-.07-.129t-.093-.114q-.053-.052-.114-.093t-.13-.069t-.14-.043Q19.573 2 19.499 2t-.146.015q-.073.014-.141.042t-.129.07t-.114.093q-.052.053-.093.114L15.599 7.25H7.5q-1.76 0-3.005 1.245T3.25 11.5v5q0 1.76 1.245 3.005T7.5 20.75h9q1.76 0 3.005-1.245T20.75 16.5v-5q0-1.76-1.245-3.005M10.5 10.25q3.354 0 3.708 3H16.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2.292q-.354 3-3.708 3q-3.75 0-3.75-3.75t3.75-3.75");
}

</style>
