<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8c7wabst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-image-24-filled" /></template>
<style>
.c8c7wabst {
  fill: currentColor;
  d: path("M14.793 17.268a1 1 0 0 1 1.414 0l4.25 4.249A3.24 3.24 0 0 1 18.75 22h-6.5c-.626 0-1.21-.177-1.706-.483zM18.75 9A3.25 3.25 0 0 1 22 12.25v6.5c0 .626-.177 1.21-.483 1.706l-4.25-4.249a2.5 2.5 0 0 0-3.535 0l-4.249 4.25A3.24 3.24 0 0 1 9 18.75v-6.5A3.25 3.25 0 0 1 12.25 9zM9.5 2a7.5 7.5 0 0 1 7.35 6h-4.6A4.25 4.25 0 0 0 8 12.25v4.6A7.5 7.5 0 0 1 9.5 2m8.5 9.75a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5");
}

</style>
