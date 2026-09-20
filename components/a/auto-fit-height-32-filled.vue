<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wic_mjbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:auto-fit-height-32-filled" /></template>
<style>
.wic_mjbbn {
  fill: currentColor;
  d: path("M24.878 26.507a1.25 1.25 0 0 1 0 2.486L24.75 29H7.25a1.25 1.25 0 1 1 0-2.5h17.5zM15.21 7.28a1.25 1.25 0 0 1 1.673.086l3.75 3.75l.086.095a1.25 1.25 0 0 1-1.76 1.759l-.094-.086l-1.616-1.616v9.464l1.616-1.616a1.25 1.25 0 0 1 1.768 1.768l-3.75 3.75a1.25 1.25 0 0 1-1.768 0l-3.75-3.75l-.086-.095a1.25 1.25 0 0 1 1.76-1.759l.094.086l1.616 1.616v-9.464l-1.616 1.616a1.25 1.25 0 0 1-1.768-1.768l3.75-3.75zm9.667-4.273a1.25 1.25 0 0 1 0 2.486l-.128.007H7.25a1.25 1.25 0 1 1 0-2.5h17.5z");
}

</style>
