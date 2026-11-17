<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8lgcpflz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-loop-right-fill-round" /></template>
<style>
.x8lgcpflz {
  fill: currentColor;
  d: path("M12 17h4.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L16.586 19H12a8 8 0 1 1 8-8a1 1 0 0 1-2 0a6 6 0 0 0-2.685-5.001a6 6 0 0 0-5.65-.528A6.002 6.002 0 0 0 12 17");
}

</style>
