<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i-8l54b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:car-simple-light" /></template>
<style>
.i-8l54b4j {
  fill: currentColor;
  d: path("M240 106h-12.1l-28.31-63.69A14 14 0 0 0 186.8 34H69.2a14 14 0 0 0-12.79 8.31L28.1 106H16a6 6 0 0 0 0 12h10v82a14 14 0 0 0 14 14h24a14 14 0 0 0 14-14v-18h100v18a14 14 0 0 0 14 14h24a14 14 0 0 0 14-14v-82h10a6 6 0 0 0 0-12M67.37 47.19A2 2 0 0 1 69.2 46h117.6a2 2 0 0 1 1.83 1.19L214.77 106H41.23ZM218 200a2 2 0 0 1-2 2h-24a2 2 0 0 1-2-2v-24a6 6 0 0 0-6-6H72a6 6 0 0 0-6 6v24a2 2 0 0 1-2 2H40a2 2 0 0 1-2-2v-82h180Z");
}

</style>
