<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc85eqb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chopsticks-24-filled" /></template>
<style>
.nc85eqb9s {
  fill: currentColor;
  d: path("M5.376 2.1a.75.75 0 0 1 1.024.276L11.365 11h2.27L9.1 3.124a.75.75 0 0 1 1.3-.748L15.365 11h5.933c.388 0 .702.315.702.702V12a10 10 0 0 1-.458 3H2.458A10 10 0 0 1 2 12v-.298c0-.387.314-.702.702-.702h6.933L5.1 3.124A.75.75 0 0 1 5.376 2.1M3.067 16.5A10 10 0 0 0 12 22a10 10 0 0 0 8.933-5.5z");
}

</style>
