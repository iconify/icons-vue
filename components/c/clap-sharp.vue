<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl2piabsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clap-sharp" /></template>
<style>
.dl2piabsn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.66 8.42l.29.07l2.17.59l-.58 2.17l-1.94 7.24l-.58 2.18l-2.18-.59l-.29-.07l-2.17-.59l.58-2.17l1.94-7.24l.58-2.18zm6.39.07l.29-.07l2.18-.59l.58 2.18l1.94 7.24l.58 2.17l-2.17.59l-.29.07l-2.18.59l-.58-2.18l-1.94-7.24l-.58-2.17zM12 2.75v2M8.75 3.5L9.5 5m5.75-1.5L14.5 5");
}

</style>
