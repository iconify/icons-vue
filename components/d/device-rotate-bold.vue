<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nr-1nl1og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:device-rotate-bold" /></template>
<style>
.nr-1nl1og {
  fill: currentColor;
  d: path("m208.49 224.49l-24 24a12 12 0 0 1-17-17L171 228H80a28 28 0 0 1-28-28v-92a12 12 0 0 1 24 0v92a4 4 0 0 0 4 4h91l-3.52-3.51a12 12 0 0 1 17-17l24 24a12 12 0 0 1 .01 17M80 76a12 12 0 0 0 8.49-20.49L85 52h91a4 4 0 0 1 4 4v92a12 12 0 0 0 24 0V56a28 28 0 0 0-28-28H85l3.52-3.52a12 12 0 0 0-17-17l-24 24a12 12 0 0 0 0 17l24 24A12 12 0 0 0 80 76");
}

</style>
