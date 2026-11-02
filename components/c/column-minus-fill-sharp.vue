<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq4fn5bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:column-minus-fill-sharp" /></template>
<style>
.wq4fn5bmi {
  fill: currentColor;
  d: path("M3 20V4a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m17-9a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Z");
}

</style>
