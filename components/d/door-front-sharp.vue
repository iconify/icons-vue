<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwzwsbbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-front-sharp" /></template>
<style>
.mwzwsbbwb {
  fill: currentColor;
  d: path("M3 21h18v-2h-2V3H5v16H3zm10.288-8.287Q13 12.425 13 12t.288-.712T14 11t.713.288T15 12t-.288.713T14 13t-.712-.288");
}

</style>
