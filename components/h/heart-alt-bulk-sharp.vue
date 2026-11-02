<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3uk37b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-alt-bulk-sharp" /></template>
<style>
.y3uk37b6v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12 5.586l.293-.293a5.243 5.243 0 0 1 7.414 7.414l-7 7a1 1 0 0 1-1.414 0l-7-7a5.243 5.243 0 0 1 7.414-7.414Z");
}

</style>
