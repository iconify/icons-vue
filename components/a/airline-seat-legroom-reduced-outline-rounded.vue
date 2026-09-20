<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opgz56b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airline-seat-legroom-reduced-outline-rounded" /></template>
<style>
.opgz56b0r {
  fill: currentColor;
  d: path("M15.5 21q-.8 0-1.362-.65t-.363-1.425L15 14H8q-.825 0-1.412-.587T6 12V4q0-.425.288-.712T7 3h4q.425 0 .713.288T12 4v5h4.925q1 0 1.6.8t.325 1.75L17 18h1.45q.675 0 1.113.413T20 19.5t-.413 1.088T18.5 21zM5 17q-.825 0-1.412-.587T3 15V4q0-.425.288-.712T4 3t.713.288T5 4v11h6q.425 0 .713.288T12 16t-.288.713T11 17z");
}

</style>
