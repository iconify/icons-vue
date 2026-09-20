<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q52jowl2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lightbulb-2" /></template>
<style>
.q52jowl2a {
  fill: currentColor;
  d: path("M10 18q-.825 0-1.412-.587T8 16v-1.25q-1.425-.975-2.212-2.5T5 9q0-2.925 2.038-4.962T12 2t4.963 2.038T19 9q0 1.725-.788 3.238T16 14.75V16q0 .825-.587 1.413T14 18zm0 4q-.425 0-.712-.288T9 21v-1h6v1q0 .425-.288.713T14 22z");
}

</style>
