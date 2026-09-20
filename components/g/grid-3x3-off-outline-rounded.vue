<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrrj0y64a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grid-3x3-off-outline-rounded" /></template>
<style>
.lrrj0y64a {
  fill: currentColor;
  d: path("m18.825 16l-2-2H19q.425 0 .713.288T20 15t-.288.713T19 16zM16 13.175L10.825 8H14V5q0-.425.288-.712T15 4t.713.288T16 5v3h3q.425 0 .713.288T20 9t-.288.713T19 10h-3zm-6-6l-2-2V5q0-.425.288-.712T9 4t.713.288T10 5zm4 9.65L13.175 16H10v3q0 .425-.288.713T9 20t-.712-.288T8 19v-3H5q-.425 0-.712-.288T4 15t.288-.712T5 14h3v-3.175L7.175 10H5q-.425 0-.712-.287T4 9t.288-.712T5 8h.175L2.1 4.925q-.3-.3-.3-.7t.3-.7t.713-.3t.712.3L20.475 20.5q.3.3.3.7t-.3.7t-.7.3t-.7-.3L16 18.825V19q0 .425-.288.713T15 20t-.712-.288T14 19z");
}

</style>
