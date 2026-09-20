<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3_s7hbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cellular-data-4-24-filled" /></template>
<style>
.l3_s7hbus {
  fill: currentColor;
  d: path("M8 14c.552 0 1 .445 1 .994v4.012c0 .549-.448.994-1 .994s-1-.445-1-.994v-4.012A.997.997 0 0 1 8 14m-4 3c.552 0 1 .44 1 .984v1.032A.99.99 0 0 1 4 20c-.552 0-1-.44-1-.984v-1.032A.99.99 0 0 1 4 17");
}

</style>
