<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep_ihac0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-right-fill" /></template>
<style>
.ep_ihac0v {
  fill: currentColor;
  d: path("M3 10a2 2 0 0 1 2-2h6V5a1.25 1.25 0 0 1 .14-.582c.371-.712 1.242-.835 1.932-.549c.237.098.453.242.635.424l6 6a2.414 2.414 0 0 1 0 3.414l-6 6a2 2 0 0 1-.635.424c-.69.286-1.561.163-1.932-.549A1.25 1.25 0 0 1 11 19v-3H5a2 2 0 0 1-2-2Z");
}

</style>
