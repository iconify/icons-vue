<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uvg4vfb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:column-48-regular" /></template>
<style>
.uvg4vfb_m {
  fill: currentColor;
  d: path("M10.75 6A4.25 4.25 0 0 1 15 10.25v27.5A4.25 4.25 0 0 1 10.75 42h-3.5a1.25 1.25 0 1 1 0-2.5h3.5a1.75 1.75 0 0 0 1.75-1.75v-27.5a1.75 1.75 0 0 0-1.75-1.75h-3.5a1.25 1.25 0 1 1 0-2.5zm16 0A4.25 4.25 0 0 1 31 10.25v27.5A4.25 4.25 0 0 1 26.75 42h-5.5A4.25 4.25 0 0 1 17 37.75v-27.5A4.25 4.25 0 0 1 21.25 6zm14 0a1.25 1.25 0 1 1 0 2.5h-3.5a1.75 1.75 0 0 0-1.75 1.75v27.5c0 .967.783 1.75 1.75 1.75h3.5a1.25 1.25 0 1 1 0 2.5h-3.5A4.25 4.25 0 0 1 33 37.75v-27.5A4.25 4.25 0 0 1 37.25 6zm-19.5 2.5a1.75 1.75 0 0 0-1.75 1.75v27.5c0 .967.784 1.75 1.75 1.75h5.5a1.75 1.75 0 0 0 1.75-1.75v-27.5a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
