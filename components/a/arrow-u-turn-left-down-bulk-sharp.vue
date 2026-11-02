<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndfwqccne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-left-down-bulk-sharp" /></template>
<style>
.ndfwqccne {
  fill: currentColor;
  d: path("m8.293 21.707l-4-4a.999.999 0 1 1 1.414-1.414L8 18.586V3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v10a1 1 0 0 1-2 0V4h-8v14.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0");
}

</style>
