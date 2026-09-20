<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvqenacld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flip-vertical-24-regular" /></template>
<style>
.wvqenacld {
  fill: currentColor;
  d: path("M19.656 2.12a.75.75 0 0 1 .344.63v7.5a.75.75 0 0 1-.75.75H2.75a.75.75 0 0 1-.31-1.433l16.5-7.5a.75.75 0 0 1 .716.052M6.213 9.5H18.5V3.915zM20 21.5a.5.5 0 0 1-.713.452l-17-8A.5.5 0 0 1 2.5 13h17a.5.5 0 0 1 .5.5z");
}

</style>
