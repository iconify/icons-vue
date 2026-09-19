<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i774tr1hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-new-label" /></template>
<style>
.i774tr1hp {
  fill: currentColor;
  d: path("m21 12l-4.37 6.16c-.37.52-.98.84-1.63.84h-3v-6H9v-3H3V7c0-1.1.9-2 2-2h10c.65 0 1.26.31 1.63.84zm-11 3H7v-3H5v3H2v2h3v3h2v-3h3z");
}

</style>
