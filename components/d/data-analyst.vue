<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwi1btb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-analyst" /></template>
<style>
.gwi1btb7z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 7.5q0-1.968 1.391-3.359T11 2.75t3.359 1.391T15.75 7.5t-1.391 3.359T11 12.25t-3.359-1.391T6.25 7.5M11 13.75q1.674 0 3.081.391Q12.5 15.743 12.5 18q0 2.181 1.476 3.75H4.5q-1.75 0-1.75-1.75q0-2.798 2.468-4.577Q7.538 13.75 11 13.75m3.995 1.245q1.244-1.244 3.003-1.245H18q1.76 0 3.005 1.245T22.25 18t-1.245 3.005T18 22.25t-3.005-1.245T13.75 18t1.245-3.005M17.25 18v-2.69q-2 .345-2 2.69q0 2.75 2.75 2.75q1.139 0 1.945-.805q.526-.527.708-1.195H18q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T17.25 18m2.883-1.738q-.088-.106-.188-.207q-.527-.526-1.195-.708v1.903h1.903q-.147-.541-.52-.988");
}

</style>
