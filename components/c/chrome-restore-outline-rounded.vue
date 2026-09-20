<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9vjnhbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-restore-outline-rounded" /></template>
<style>
.y9vjnhbbz {
  fill: currentColor;
  d: path("M10 16q-.825 0-1.413-.588T8 14V6q0-.825.588-1.413T10 4h8q.825 0 1.413.588T20 6v8q0 .825-.588 1.413T18 16h-8Zm0-10v8h8V6h-8ZM6 20q-.825 0-1.413-.588T4 18V9.525q0-.425.288-.713T5 8.525q.425 0 .713.288T6 9.524V18h8.475q.425 0 .713.288t.287.712q0 .425-.287.713t-.713.287H6Zm4-14v8v-8Z");
}

</style>
