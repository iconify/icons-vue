<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fkx47qb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:briefcase-32-filled" /></template>
<style>
.fkx47qb8p {
  fill: currentColor;
  d: path("M30 23.5a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 23.5v-6.312A6.48 6.48 0 0 0 6.5 19H13v.5a1.5 1.5 0 0 0 1.5 1.5h3a1.5 1.5 0 0 0 1.5-1.5V19h6.5c1.747 0 3.332-.69 4.5-1.812zM19 3a3 3 0 0 1 3 3v2h3.5a4.5 4.5 0 0 1 0 9H19v-.5a1.5 1.5 0 0 0-1.5-1.5h-3a1.5 1.5 0 0 0-1.5 1.5v.5H6.5a4.5 4.5 0 1 1 0-9H10V6a3 3 0 0 1 3-3zm-6 2a1 1 0 0 0-1 1v2h8V6a1 1 0 0 0-1-1z");
}

</style>
