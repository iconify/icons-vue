<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5gb_xkyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gift-fill-round" /></template>
<style>
.u5gb_xkyq {
  fill: currentColor;
  d: path("M9.707 3.293L12 5.586l2.293-2.293c.359-.36.798-.63 1.281-.789s.997-.209 1.497-.11a2.3 2.3 0 0 1 1.395.858C18.849 3.753 19 4.378 19 5c0 .344-.069.685-.206 1H19a3.002 3.002 0 0 1 2.829 4H13V8h-2v2H2.171A3 3 0 0 1 5 6h.206A2.5 2.5 0 0 1 5 5c0-.622.151-1.247.534-1.748a2.3 2.3 0 0 1 1.395-.858c.5-.099 1.015-.05 1.497.11c.483.159.922.429 1.281.789M15 6c.552 0 1.195-.084 1.65-.425c.185-.139.35-.332.35-.575c0-.252-.024-.585-.321-.644a.9.9 0 0 0-.472.046c-.188.062-.36.165-.5.305L14.414 6ZM9.586 6L8.293 4.707a1.3 1.3 0 0 0-.5-.305a.9.9 0 0 0-.472-.046C7.024 4.415 7 4.748 7 5c0 .243.165.436.35.575C7.805 5.916 8.448 6 9 6ZM11 12v10H9a5 5 0 0 1-5-5v-5Zm9 0v5a5 5 0 0 1-5 5h-2V12Z");
}

</style>
