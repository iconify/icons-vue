<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi962hjnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calculator-fill-sharp" /></template>
<style>
.mi962hjnb {
  fill: currentColor;
  d: path("M3 3a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Zm5 4a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Zm.01 4H8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m4 0H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M17 16v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m-9-1a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4.01 0H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
