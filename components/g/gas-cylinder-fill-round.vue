<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1j1daciq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gas-cylinder-fill-round" /></template>
<style>
.q1j1daciq {
  fill: currentColor;
  d: path("M10 2h4a3 3 0 0 1 2.806 4.064A5.005 5.005 0 0 1 21 11v1H3v-1a5.005 5.005 0 0 1 4.194-4.936A3.002 3.002 0 0 1 10 2M9 4v2h6V4ZM3 14h18v1a5.01 5.01 0 0 1-4 4.901V21a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-1.099A5.01 5.01 0 0 1 3 15Z");
}

</style>
