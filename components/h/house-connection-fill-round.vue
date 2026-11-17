<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfhy2b_qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-connection-fill-round" /></template>
<style>
.mfhy2b_qt {
  fill: currentColor;
  d: path("M15.222 18H13v2h7a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h7v-2H8.778a4 4 0 0 1-4-4V9.806c0-1.154.498-2.251 1.366-3.011l3.222-2.819a4 4 0 0 1 5.268 0l3.222 2.819a4 4 0 0 1 1.366 3.011V14a4 4 0 0 1-4 4");
}

</style>
