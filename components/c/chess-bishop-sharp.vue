<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6ev4k0rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chess-bishop-sharp" /></template>
<style>
.s6ev4k0rd {
  fill: currentColor;
  d: path("M4 22v-5q1.375-.95 2.488-2.2T8.25 12H6v-2h1.8L6 7l6-6l6 6l-1.8 3H18v2h-2.25q.65 1.55 1.763 2.8T20 17v5zm8.713-14.288Q13 7.425 13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8t.713-.288");
}

</style>
