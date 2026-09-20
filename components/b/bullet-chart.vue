<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io8ni7dmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bullet-chart" /></template>
<style>
.io8ni7dmr {
  fill: currentColor;
  d: path("M2 19V5h9V3h2v2h9v14h-9v2h-2v-2zm2-2h7v-2H4zm0-8h7V7H4zm9 8h7V7h-7v2h3v6h-3z");
}

</style>
