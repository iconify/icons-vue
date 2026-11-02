<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfsnvedme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-fill-round" /></template>
<style>
.qfsnvedme {
  fill: currentColor;
  d: path("M9 2h6c.898 0 1.928.572 2.089 1.521a1.34 1.34 0 0 1-.382 1.186l-3 3a2.414 2.414 0 0 1-3.414 0l-3-3a1.36 1.36 0 0 1-.382-1.186C7.072 2.572 8.102 2 9 2m-2 9a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm6 2h-2a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2m6-2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm-4 11H9c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l3-3a2.414 2.414 0 0 1 3.414 0l3 3c.311.31.456.752.382 1.186C16.928 21.428 15.898 22 15 22");
}

</style>
