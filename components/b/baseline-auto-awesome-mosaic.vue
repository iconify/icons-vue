<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie6bbu6yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-auto-awesome-mosaic" /></template>
<style>
.ie6bbu6yu {
  fill: currentColor;
  d: path("M3 5v14a2 2 0 0 0 2 2h6V3H5a2 2 0 0 0-2 2m16-2h-6v8h8V5c0-1.1-.9-2-2-2m-6 18h6c1.1 0 2-.9 2-2v-6h-8z");
}

</style>
