<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmly1d4do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camera-roll" /></template>
<style>
.wmly1d4do {
  fill: currentColor;
  d: path("M4.616 21q-.667 0-1.141-.475T3 19.386V5.615q0-.666.475-1.14T4.615 4H6V2.846q0-.36.243-.603T6.846 2h2.308q.36 0 .603.243t.243.603V4h1.385q.666 0 1.14.475T13 5.615V6h8v13h-8.038v.385q0 .666-.464 1.14T11.385 21zm4.807-4.192h1.539v-1.539H9.423zm0-7.077h1.539V8.192H9.423zm3.923 7.077h1.539v-1.539h-1.539zm0-7.077h1.539V8.192h-1.539zm3.923 7.077h1.539v-1.539h-1.539zm0-7.077h1.539V8.192h-1.539z");
}

</style>
