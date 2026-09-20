<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kupqwnbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:android-cell-4-bar-plus" /></template>
<style>
.kupqwnbur {
  fill: currentColor;
  d: path("M1.5 20v-8h3v8zm6 0V9.5h3V20zm12-7.975V4h3v8.675q-.675-.4-1.437-.562t-1.563-.088M13.5 20V7h3v6.425q-.7.675-1.1 1.6T15 17q0 .85.263 1.613T16 20zm5.5 0v-2h-2v-2h2v-2h2v2h2v2h-2v2z");
}

</style>
