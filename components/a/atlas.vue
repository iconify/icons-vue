<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uh2ak3vlm"/><path class="wtd1eevdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:atlas" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.uh2ak3vlm {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 8.657l-3.652 8.264c-.118.263-.185.479-.447.479H5.483c-.344 0-.534-.098-.36-.479l5.894-13.53c.118-.226.196-.391.463-.391h1.044c.262 0 .334.165.463.39l5.893 13.526c.17.386-.025.484-.37.484h-2.412c-.262 0-.334-.216-.447-.479l-3.652-8.27z");
}

.wtd1eevdu {
  fill: var(--svg-color--3ff, #3ff);
  d: path("m12.005 21l-2.412-4.63h4.741z");
}

</style>
