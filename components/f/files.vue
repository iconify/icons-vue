<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k04_w5b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:files" /></template>
<style>
.k04_w5b4n {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18v-3h9q.825 0 1.413-.587T13 13V4h7q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm-2-6V8q0-.825.588-1.412T4 6h6zm3.825-1L11 7.825V13z");
}

</style>
