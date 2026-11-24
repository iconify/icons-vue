<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx48rybny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:corner-sharp-fill-sharp" /></template>
<style>
.qx48rybny {
  fill: currentColor;
  d: path("M4 5a1 1 0 0 1 1-1h14a1 1 0 0 1 0 2H6v13a1 1 0 0 1-2 0Z");
}

</style>
