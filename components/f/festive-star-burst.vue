<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj7d3bs9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:festive-star-burst" /></template>
<style>
.dj7d3bs9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.808 7.388l.456 1.065a1.5 1.5 0 0 0 1.244.903l1.153.105a.879.879 0 0 1 .5 1.537l-.872.763a1.5 1.5 0 0 0-.475 1.461l.257 1.13a.879.879 0 0 1-1.308.95l-.994-.593a1.5 1.5 0 0 0-1.538 0l-.994.593a.879.879 0 0 1-1.308-.95l.257-1.13a1.5 1.5 0 0 0-.475-1.461l-.872-.763a.879.879 0 0 1 .5-1.537l1.153-.105a1.5 1.5 0 0 0 1.244-.903l.456-1.065a.879.879 0 0 1 1.616 0M16.25 5.75l1.25-2m1.25 10l2.25.75m-9 4V21m-6.75-7.25L3 14.5m4.75-8.75l-1.25-2");
}

</style>
