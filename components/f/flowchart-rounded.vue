<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwep62bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flowchart-rounded" /></template>
<style>
.nwep62bob {
  fill: currentColor;
  d: path("M15 20v-2h-4v-5H9v2H2V9h7v2h2V6h4V4h7v6h-7V8h-2v8h2v-2h7v6z");
}

</style>
