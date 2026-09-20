<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi--2hb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fullscreen-exit-outline-rounded" /></template>
<style>
.pi--2hb9q {
  fill: currentColor;
  d: path("M6 18H4q-.425 0-.712-.288T3 17t.288-.712T4 16h3q.425 0 .713.288T8 17v3q0 .425-.288.713T7 21t-.712-.288T6 20zm12 0v2q0 .425-.288.713T17 21t-.712-.288T16 20v-3q0-.425.288-.712T17 16h3q.425 0 .713.288T21 17t-.288.713T20 18zM6 6V4q0-.425.288-.712T7 3t.713.288T8 4v3q0 .425-.288.713T7 8H4q-.425 0-.712-.288T3 7t.288-.712T4 6zm12 0h2q.425 0 .713.288T21 7t-.288.713T20 8h-3q-.425 0-.712-.288T16 7V4q0-.425.288-.712T17 3t.713.288T18 4z");
}

</style>
