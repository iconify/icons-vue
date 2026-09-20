<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lyspszbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:framer-logo-thin" /></template>
<style>
.lyspszbwv {
  fill: currentColor;
  d: path("M204 104V40a4 4 0 0 0-4-4H56a4 4 0 0 0-2.66 7l64.14 57H56a4 4 0 0 0-4 4v64a4 4 0 0 0 1.17 2.83l72 72A4 4 0 0 0 132 240v-68h68a4 4 0 0 0 2.66-7l-64.14-57H200a4 4 0 0 0 4-4m-14.52 60H128a4 4 0 0 0-4 4v62.34l-64-64V108h66.48Zm6.52-64h-66.48l-63-56H196Z");
}

</style>
