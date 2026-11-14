<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vridpey5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:long-term-liabilities" /></template>
<style>
.vridpey5d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4.25h10q2.75 0 2.75 2.75q0 .74-.199 1.281q2.199.26 2.199 2.719q0 1.205-.528 1.882q-.584-.132-1.222-.132q-2.175 0-3.712 1.538q-1.449 1.448-1.533 3.462H5q-2.75 0-2.75-2.75q0-2.459 2.199-2.719Q4.25 11.74 4.25 11t.199-1.281Q2.25 9.459 2.25 7q0-2.75 2.75-2.75M22 18q0-4-4-4t-4 4t4 4t4-4m-4 2.5q-2.5 0-2.5-2.5t2.5-2.5t2.5 2.5t-2.5 2.5m.75-4v1.14l.969.774q.057.046.105.103t.083.121q.036.065.058.135t.03.144t.002.147q-.006.074-.027.145t-.054.136q-.034.066-.08.124t-.103.105t-.121.083t-.135.058t-.144.03t-.147.002t-.145-.027t-.136-.054q-.066-.034-.124-.08l-1.25-1q-.065-.053-.118-.119t-.089-.142t-.055-.158T17.25 18v-1.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
