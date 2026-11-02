<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew-1spsen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-right-up-bulk-sharp" /></template>
<style>
.ew-1spsen {
  fill: currentColor;
  d: path("m15.707 2.293l4 4a.999.999 0 1 1-1.414 1.414L16 5.414V21a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V11a1 1 0 0 1 2 0v9h8V5.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414l4-4a1 1 0 0 1 1.405-.009z");
}

</style>
