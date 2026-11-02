<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj-44zbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-fill-sharp" /></template>
<style>
.hj-44zbru {
  fill: currentColor;
  d: path("m16.293 12.293l2-2a3.243 3.243 0 0 0-4.586-4.586l-2 2a.999.999 0 1 1-1.414-1.414l2-2a5.243 5.243 0 0 1 7.414 7.414l-2 2a.999.999 0 1 1-1.414-1.414m-9 3l8-8a.999.999 0 1 1 1.414 1.414l-8 8a.999.999 0 1 1-1.414-1.414m.414-3.586l-2 2a3.243 3.243 0 0 0 4.586 4.586l2-2a.999.999 0 1 1 1.414 1.414l-2 2a5.243 5.243 0 0 1-7.414-7.414l2-2a.999.999 0 1 1 1.414 1.414");
}

</style>
