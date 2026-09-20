<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-sry2b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:book-5-outline-rounded" /></template>
<style>
.q-sry2b-p {
  fill: currentColor;
  d: path("M6.75 22q-1.125 0-1.937-.763T4 19.35V5.4q0-.95.588-1.7t1.537-.95l7.5-1.475q.925-.2 1.65.4T16 3.225V15.15q0 .725-.45 1.288t-1.15.687L6.525 18.7q-.225.05-.375.238T6 19.35q0 .275.225.463T6.75 20H18V5q0-.425.288-.712T19 4t.713.288T20 5v15q0 .825-.587 1.413T18 22zM9 16.175l5-.975V3.25l-5 .975zm-2 .4V4.625l-.375.075q-.275.05-.45.238T6 5.4v11.425q.125-.05.263-.087t.262-.063zM6 4.7v12.125z");
}

</style>
