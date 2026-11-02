<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukcc3lbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:column-minus-fill-round" /></template>
<style>
.ukcc3lbke {
  fill: currentColor;
  d: path("M3 7a4 4 0 0 1 8 0v10a4 4 0 0 1-8 0Zm17 4a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Z");
}

</style>
