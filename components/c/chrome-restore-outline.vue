<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xeg22cbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-restore-outline" /></template>
<style>
.xeg22cbqx {
  fill: currentColor;
  d: path("M10 16q-.825 0-1.413-.588T8 14V6q0-.825.588-1.413T10 4h8q.825 0 1.413.588T20 6v8q0 .825-.588 1.413T18 16h-8Zm0-10v8h8V6h-8ZM6 20q-.825 0-1.413-.588T4 18V8.525h2V18h9.475v2H6Zm4-14v8v-8Z");
}

</style>
