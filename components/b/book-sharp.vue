<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf6fnmbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:book-sharp" /></template>
<style>
.qf6fnmbaw {
  fill: currentColor;
  d: path("M4 22V2h16v20zm7-11l2.5-1.5L16 11V4h-5z");
}

</style>
