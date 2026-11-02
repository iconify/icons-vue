<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_nbxrbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-pound-fill" /></template>
<style>
.b_nbxrbow {
  fill: currentColor;
  d: path("M10 9v4h3a1 1 0 0 1 0 2h-3v3h8a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2h2v-3H6a1 1 0 0 1 0-2h2V9a5 5 0 0 1 10 0a1 1 0 0 1-2 0a3 3 0 1 0-6 0");
}

</style>
