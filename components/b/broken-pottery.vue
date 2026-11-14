<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea0hnj-4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:broken-pottery" /></template>
<style>
.ea0hnj-4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.67 7.498L7.507 4.62a1.5 1.5 0 0 1 2.265.579l1.338 2.944a1.5 1.5 0 0 1-.213 1.581l-1.381 1.657a1.5 1.5 0 0 0-.284 1.391l.84 2.801a1.5 1.5 0 0 1-.996 1.865l-3.308 1.018a1.5 1.5 0 0 1-1.935-1.298l-.757-8.324a1.5 1.5 0 0 1 .594-1.336m12.717-3.447l2.593.598a1.5 1.5 0 0 1 1.109 1.856l-.69 2.53a1.5 1.5 0 0 1-1.859 1.048l-1.207-.345A1.5 1.5 0 0 1 15.29 8.66l-.696-2.784a1.5 1.5 0 0 1 1.793-1.825m-1.167 9.338l3.028-.275a1.5 1.5 0 0 1 1.583 1.099l.845 3.101a1.5 1.5 0 0 1-.776 1.736l-2.092 1.046a1.5 1.5 0 0 1-1.543-.121l-2.049-1.463a1.5 1.5 0 0 1-.619-1.387l.268-2.408a1.5 1.5 0 0 1 1.355-1.328");
}

</style>
