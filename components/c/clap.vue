<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grd3_4p1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clap" /></template>
<style>
.grd3_4p1p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.66 8.42l.29.07q2.17.59 1.59 2.76L8.6 18.49q-.58 2.18-2.76 1.59l-.29-.07q-2.17-.59-1.59-2.76l1.94-7.24q.58-2.18 2.76-1.59m6.39.07l.29-.07q2.18-.59 2.76 1.59l1.94 7.24q.58 2.17-1.59 2.76l-.29.07q-2.18.59-2.76-1.59l-1.94-7.24q-.58-2.17 1.59-2.76M12 2.75v2M8.75 3.5L9.5 5m5.75-1.5L14.5 5");
}

</style>
