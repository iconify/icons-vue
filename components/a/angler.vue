<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7aym8bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:angler" /></template>
<style>
.u7aym8bno {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 13.25q2.052 0 3.704.588l4.603-11.124v-.001q.043-.103.113-.189t.163-.148q.093-.061.199-.094q.107-.032.218-.032h.012q.143.002.275.057q.138.057.243.162q.106.106.163.244T20.25 3v8q0 .5.5.5t.5-.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 2-2 2t-2-2V6.774l-3.182 7.689q.37.212.714.46q2.468 1.779 2.468 4.577q0 1.75-1.75 1.75H4q-1.75 0-1.75-1.75q0-2.798 2.468-4.577q2.32-1.673 5.782-1.673M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7");
}

</style>
