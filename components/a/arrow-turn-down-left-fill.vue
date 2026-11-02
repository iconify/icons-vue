<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7gzbx51d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-down-left-fill" /></template>
<style>
.s7gzbx51d {
  fill: currentColor;
  d: path("M18 14a3 3 0 0 1-3 3H9.414l3.293 3.293a.999.999 0 1 1-1.414 1.414l-5-5a1 1 0 0 1 0-1.414l5-5a.999.999 0 1 1 1.414 1.414L9.414 15H15a.997.997 0 0 0 1-1V3a1 1 0 0 1 2 0Z");
}

</style>
