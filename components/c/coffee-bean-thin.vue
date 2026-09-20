<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="k74b8zbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:coffee-bean-thin" /></template>
<style>
.k74b8zbob {
  fill: currentColor;
  d: path("M209 47c-32.36-32.35-95-22.33-139.7 22.34S14.63 176.66 47 209c12.82 12.81 30.38 19 49.71 19c29.46 0 63-14.34 90-41.32C231.35 142 241.37 79.34 209 47M75 75c25.47-25.46 57-39.09 84.26-39.09c14.51 0 27.83 3.87 38.43 11.84c-25.76 7.05-63 26.4-73.6 79.49c-10.5 52.52-49.25 69.26-72.91 74.58C23.77 172.12 34.16 115.81 75 75m106 106c-39 39-92.17 50.23-122.71 27.25c25.75-7 63-26.39 73.62-79.48c10.5-52.53 49.25-69.26 72.91-74.59C232.23 83.88 221.84 140.19 181 181");
}

</style>
