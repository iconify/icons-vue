<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1ci11bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-castle" /></template>
<style>
.z1ci11bqh {
  fill: currentColor;
  d: path("M21 9v2h-2V3h-2v2h-2V3h-2v2h-2V3H9v2H7V3H5v8H3V9H1v12h9v-3c0-1.1.9-2 2-2s2 .9 2 2v3h9V9zm-10 3H9V9h2zm4 0h-2V9h2z");
}

</style>
