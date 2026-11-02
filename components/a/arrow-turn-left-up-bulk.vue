<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joarb8t4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-left-up-bulk" /></template>
<style>
.joarb8t4u {
  fill: currentColor;
  d: path("M9 9.414V15a.997.997 0 0 0 1 1h11a1 1 0 0 1 0 2H10a3 3 0 0 1-3-3V9.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414l5-5a.997.997 0 0 1 1.414 0l5 5a.999.999 0 1 1-1.414 1.414Z");
}

</style>
