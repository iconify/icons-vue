<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_mnzywuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-alt-off-outline-rounded" /></template>
<style>
.e_mnzywuv {
  fill: currentColor;
  d: path("m14.8 11.975l-1.425-1.425L16.95 6H8.825l-2-2H19q.625 0 .9.55t-.1 1.05zm-.8 4.85V19q0 .425-.288.713T13 20h-2q-.425 0-.712-.288T10 19v-6.175l-7.9-7.9q-.275-.275-.275-.687t.275-.713q.3-.3.713-.3t.712.3L20.5 20.5q.3.3.288.7t-.313.7q-.3.275-.7.288t-.7-.288zm-.625-6.275");
}

</style>
