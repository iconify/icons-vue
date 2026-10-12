<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j64j93baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gem-sharp" /></template>
<style>
.j64j93baj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.4 7.75h8.1l.62.66l2.76 2.93l.62.66l-.61.66l-7.28 7.93l-.61.66l-.61-.66l-7.28-7.93L3.5 12l.62-.66l2.76-2.93l.62-.66zM3.75 12h16.5M10 7.75L9 12m5-4.25L15 12m3.5-9.25l.24 1.76l1.76.24l-1.76.24l-.24 1.76l-.24-1.76l-1.76-.24l1.76-.24z");
}

</style>
