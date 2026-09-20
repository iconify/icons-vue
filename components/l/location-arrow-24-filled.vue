<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxl_aabpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-arrow-24-filled" /></template>
<style>
.jxl_aabpi {
  fill: currentColor;
  d: path("M21.896 4.042c.467-1.213-.725-2.405-1.938-1.938L2.962 8.64c-1.36.522-1.252 2.48.156 2.85l7.011 1.845a.75.75 0 0 1 .535.535l1.845 7.01c.37 1.409 2.328 1.516 2.85.157z");
}

</style>
