<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuazlqlmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-maximize-outline" /></template>
<style>
.cuazlqlmn {
  fill: currentColor;
  d: path("M6 20q-.825 0-1.413-.588T4 18V6q0-.825.588-1.413T6 4h12q.825 0 1.413.588T20 6v12q0 .825-.588 1.413T18 20H6Zm0-2h12V6H6v12ZM6 6v12V6Z");
}

</style>
