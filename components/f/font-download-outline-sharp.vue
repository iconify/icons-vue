<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy63upfgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:font-download-outline-sharp" /></template>
<style>
.cy63upfgy {
  fill: currentColor;
  d: path("M6.4 18h2.1l1.1-3.05h4.8L15.5 18h2.1L13.05 6h-2.1zm3.8-4.8l1.75-4.95h.1l1.75 4.95zM2 22V2h20v20zm2-2h16V4H4zm0 0V4z");
}

</style>
