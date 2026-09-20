<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fnbinfbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-settings-32-light" /></template>
<style>
.fnbinfbcg {
  fill: currentColor;
  d: path("M7.5 3A4.5 4.5 0 0 0 3 7.5v17A4.5 4.5 0 0 0 7.5 29h8.875a9 9 0 0 1-.671-1H7.5A3.5 3.5 0 0 1 4 24.5v-8h13.843a9 9 0 0 1 1.53-1H4v-8A3.5 3.5 0 0 1 7.5 4h17A3.5 3.5 0 0 1 28 7.5v8.204q.524.303 1 .671V7.5A4.5 4.5 0 0 0 24.5 3zm11.343 16.536a1.52 1.52 0 0 1-1.117 1.928l-1.536.35a7.5 7.5 0 0 0-.04 3.19l1.698.423a1.52 1.52 0 0 1 1.096 1.892l-.496 1.724a7.5 7.5 0 0 0 2.75 1.597l1.26-1.3a1.53 1.53 0 0 1 2.193 0l1.236 1.272a7.5 7.5 0 0 0 2.737-1.635l-.467-1.514a1.52 1.52 0 0 1 1.117-1.927l1.536-.351a7.5 7.5 0 0 0 .04-3.189l-1.698-.423a1.52 1.52 0 0 1-1.096-1.893l.496-1.724a7.5 7.5 0 0 0-2.75-1.596l-1.26 1.3a1.53 1.53 0 0 1-2.193 0l-1.236-1.272a7.5 7.5 0 0 0-2.737 1.635zM25.5 23.5a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

</style>
