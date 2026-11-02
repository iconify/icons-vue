<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtc2q-bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-fill" /></template>
<style>
.gtc2q-bae {
  fill: currentColor;
  d: path("M19 2a3 3 0 0 1 3 3v11.586l-3.293-3.293a2.414 2.414 0 0 0-3.414 0l-1 1a.414.414 0 0 1-.586 0l-3-3a2.414 2.414 0 0 0-3.414 0L2 16.586V5a3 3 0 0 1 3-3Zm-6 6a2 2 0 1 0 3.999.001A2 2 0 0 0 13 8m8.707 11.121q.121.122.277.196A3 3 0 0 1 19 22H5a3 3 0 0 1-2.984-2.683a1 1 0 0 0 .277-.196l6.414-6.414a.414.414 0 0 1 .586 0l3 3a2.414 2.414 0 0 0 3.414 0l1-1a.414.414 0 0 1 .586 0Z");
}

</style>
