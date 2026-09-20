<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="wg_r-tklo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-arrow-28-regular" /></template>
<style>
.wg_r-tklo {
  fill: currentColor;
  d: path("M25.897 4.042c.467-1.213-.725-2.405-1.938-1.938L2.962 10.179c-1.36.523-1.252 2.48.156 2.851l8.96 2.358a.75.75 0 0 1 .535.534l2.358 8.96c.37 1.408 2.328 1.516 2.85.157zm-1.4-.538L16.421 24.5l-2.358-8.96a2.25 2.25 0 0 0-1.603-1.604L3.5 11.58z");
}

</style>
