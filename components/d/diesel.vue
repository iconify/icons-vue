<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y272mpnow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:diesel" /></template>
<style>
.y272mpnow {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 2.25H7q-1.76 0-3.005 1.245T2.75 6.5V18q0 1.76 1.245 3.005T7 22.25h4.5q1.76 0 3.005-1.245T15.75 18v-4.75h1q.25 0 .25.25V17q0 2.25 2.25 2.25T21.5 17V8q0-.149-.057-.287t-.163-.243l-2.5-2.5q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T17.5 5.5t.057.287t.163.243L20 8.311V17q0 .75-.75.75T18.5 17v-3.5q0-1.75-1.75-1.75h-1V6.5q0-1.76-1.245-3.005T11.5 2.25m-5 14.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.75 16V8q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014H8q1.968 0 3.359 1.391T12.75 12t-1.391 3.359T8 16.75zm.75-8v6.5H8q3.25 0 3.25-3.25T8 8.75z");
}

</style>
