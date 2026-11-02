<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7rjugupz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-bulk-sharp" /></template>
<style>
.s7rjugupz {
  fill: currentColor;
  d: path("m11.293 19.707l-5-5a.999.999 0 1 1 1.414-1.414L11 16.586V5a1 1 0 0 1 2 0v11.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-5 5a1 1 0 0 1-1.414 0");
}

</style>
