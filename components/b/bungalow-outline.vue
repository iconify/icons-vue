<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t78rnv9yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bungalow-outline" /></template>
<style>
.t78rnv9yz {
  fill: currentColor;
  d: path("M7 21v-6.2l-1.1 1.75l-1.7-1.05L12 3l7.8 12.5l-1.7 1.05L17 14.8V21zm2-2h2v-3h2v3h2v-7.4l-3-4.8l-3 4.8zm2-5v-2h2v2zm-2 5h6z");
}

</style>
