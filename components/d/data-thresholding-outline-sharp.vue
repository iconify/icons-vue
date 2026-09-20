<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1akndk-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:data-thresholding-outline-sharp" /></template>
<style>
.i1akndk-r {
  fill: currentColor;
  d: path("M4 20V4h16v16zm12.564-1H19v-2.436zM5.562 19h2.46l3-3h1.24l-3 3h2.407l3-3h1.24l-3 3h2.414l3-3H19V5H5v13.321L7.321 16h1.24zm2.088-5.712l-.689-.688l3.714-3.713l2 2L16.35 7.21l.688.689l-4.363 4.389l-2-2zM5 19V5z");
}

</style>
