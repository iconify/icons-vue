<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k34v485lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:joystick-fill" /></template>
<style>
.k34v485lb {
  fill: currentColor;
  d: path("M13 9.874V14h6a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h1v-1a1 1 0 0 1 2 0v1h3V9.874a4 4 0 1 1 2 0");
}

</style>
