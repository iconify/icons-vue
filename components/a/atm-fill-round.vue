<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6xh4h9fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:atm-fill-round" /></template>
<style>
.i6xh4h9fv {
  fill: currentColor;
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a1 1 0 0 1-2 0v-6h-2v8a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3v-8H4v6a1 1 0 0 1-2 0Zm18 2V7a3 3 0 0 0-3-3H7a3 3 0 0 0-3 3v2Zm-3-4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2ZM9 16a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
