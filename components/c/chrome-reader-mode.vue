<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy2s2dr-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-reader-mode" /></template>
<style>
.wy2s2dr-f {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm9-2h7V6h-7zm1-3h5v-1.5h-5zm0-2.5h5V11h-5zm0-2.5h5V8.5h-5z");
}

</style>
