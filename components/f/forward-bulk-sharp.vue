<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h44a4x9ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:forward-bulk-sharp" /></template>
<style>
.h44a4x9ri {
  fill: currentColor;
  d: path("M18.586 10H4v8h9a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h15.586l-2.293-2.293a.999.999 0 1 1 1.414-1.414l4 4a1 1 0 0 1 0 1.414l-4 4a.999.999 0 1 1-1.414-1.414Z");
}

</style>
