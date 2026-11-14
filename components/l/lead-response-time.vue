<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h95eaqykd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lead-response-time" /></template>
<style>
.h95eaqykd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 8.25q0-1.864 1.318-3.182T9 3.75t3.182 1.318T13.5 8.25t-1.318 3.182T9 12.75t-3.182-1.318T4.5 8.25M18 14q-4 0-4 4t4 4t4-4t-4-4m-5.25 4q0-1.352.594-2.457Q11.489 14.5 9 14.5q-2.97 0-5.037 1.485Q1.75 17.573 1.75 20q0 1.75 1.75 1.75h10.826l-.038-.038Q12.75 20.175 12.75 18M18 20.5q-2.5 0-2.5-2.5t2.5-2.5t2.5 2.5t-2.5 2.5m.75-4v1.14l.969.774q.057.046.105.103t.083.121q.036.065.058.135t.03.144t.002.147q-.006.074-.027.145t-.054.136q-.034.066-.08.124t-.103.105t-.121.083t-.135.058t-.144.03t-.147.002t-.145-.027t-.136-.054q-.066-.034-.124-.08l-1.25-1q-.065-.053-.118-.119t-.089-.142t-.055-.158T17.25 18v-1.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
