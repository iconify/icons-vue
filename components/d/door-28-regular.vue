<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="zmw-umhvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:door-28-regular" /></template>
<style>
.zmw-umhvd {
  fill: currentColor;
  d: path("M9.5 15a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3M5 5a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v18a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3zm3-1.5A1.5 1.5 0 0 0 6.5 5v18A1.5 1.5 0 0 0 8 24.5h12a1.5 1.5 0 0 0 1.5-1.5V5A1.5 1.5 0 0 0 20 3.5z");
}

</style>
