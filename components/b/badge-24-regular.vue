<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh0fj7o0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:badge-24-regular" /></template>
<style>
.eh0fj7o0q {
  fill: currentColor;
  d: path("M16.338 3A3.5 3.5 0 0 0 16 4.5H5.75c-.69 0-1.25.56-1.25 1.25v12.5c0 .69.56 1.25 1.25 1.25h12.5c.69 0 1.25-.56 1.25-1.25V8.002c.537 0 1.046-.121 1.501-.337L21 18.25A2.75 2.75 0 0 1 18.25 21H5.75A2.75 2.75 0 0 1 3 18.25V5.75A2.75 2.75 0 0 1 5.75 3zm3.162-.998a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5");
}

</style>
