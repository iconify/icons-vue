<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u61sgkbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:export-fill-sharp" /></template>
<style>
.u61sgkbon {
  fill: currentColor;
  d: path("M14.293 6.707L13 5.414V15a1 1 0 0 1-2 0V5.414L9.707 6.707a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414M5 8H4v12h16V8h-1a1 1 0 0 1 0-2h2a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h2a1 1 0 0 1 0 2");
}

</style>
