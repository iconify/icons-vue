<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0_57np6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-right-large-bulk-sharp" /></template>
<style>
.s0_57np6e {
  fill: currentColor;
  d: path("M18.586 13H3a1 1 0 0 1 0-2h15.586l-4.293-4.293a.999.999 0 1 1 1.414-1.414l6 6a1 1 0 0 1 0 1.414l-6 6a.999.999 0 1 1-1.414-1.414Z");
}

</style>
