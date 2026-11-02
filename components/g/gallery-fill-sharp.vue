<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_oqe1bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gallery-fill-sharp" /></template>
<style>
.p_oqe1bow {
  fill: currentColor;
  d: path("M8.293 6.293L2 12.586V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v9.586l-4.293-4.293a1 1 0 0 0-1.414 0L14 10.586L9.707 6.293a.997.997 0 0 0-1.414 0M17 10.414l4.707 4.707a1 1 0 0 0 .293.203V17a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-1.676a1 1 0 0 0 .293-.203L9 8.414l4.293 4.293a1 1 0 0 0 1.414 0ZM10 20a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm11 0a1 1 0 0 1 0 2h-7a1 1 0 0 1 0-2Z");
}

</style>
