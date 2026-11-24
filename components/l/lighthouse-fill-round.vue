<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofw4a48xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lighthouse-fill-round" /></template>
<style>
.ofw4a48xs {
  fill: currentColor;
  d: path("m14.735 14.368l-8.526 2.841L7.613 13H7a1 1 0 0 1 0-2h1V9a1.002 1.002 0 0 1-.707-1.707l4-4a1 1 0 0 1 1.414 0l4 4A1 1 0 0 1 16 9v2h1a1 1 0 0 1 0 2h-.613l.245.735ZM3 8h2a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m16 0h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2m-9 1v2h4V9ZM6.605 19.186l10.66-3.554L18.721 20H21a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h2.279l.14-.419Z");
}

</style>
