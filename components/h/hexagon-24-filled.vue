<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-tujgbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hexagon-24-filled" /></template>
<style>
.n-tujgbto {
  fill: currentColor;
  d: path("M8.105 3a2.25 2.25 0 0 0-1.948 1.125l-3.896 6.75a2.25 2.25 0 0 0 0 2.25l3.896 6.75A2.25 2.25 0 0 0 8.105 21h7.79a2.25 2.25 0 0 0 1.95-1.125l3.895-6.75a2.25 2.25 0 0 0 0-2.25l-3.896-6.75A2.25 2.25 0 0 0 15.895 3z");
}

</style>
