<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt4rpkbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dynamic-form-outline" /></template>
<style>
.gt4rpkbpx {
  fill: currentColor;
  d: path("M4 11q-.825 0-1.412-.587T2 9V6q0-.825.588-1.412T4 4h9v7zm0-2h7V6H4zm0 11q-.825 0-1.412-.587T2 18v-3q0-.825.588-1.412T4 13h11v7zm0-2h9v-3H4zm13 2v-9h-2V4h7l-2 5h2zM4.75 17.25h1.5v-1.5h-1.5zm0-9h1.5v-1.5h-1.5zM4 9V6zm0 9v-3z");
}

</style>
