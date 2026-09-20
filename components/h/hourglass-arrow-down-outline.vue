<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4oo_wyxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hourglass-arrow-down-outline" /></template>
<style>
.p4oo_wyxz {
  fill: currentColor;
  d: path("M8.5 11q1.05 0 1.775-.725T11 8.5V6H6v2.5q0 1.05.725 1.775T8.5 11M6 18h5v-2.5q0-1.05-.725-1.775T8.5 13t-1.775.725T6 15.5zm-3.5 2v-2H4v-2.5q0-1.05.45-1.95T5.7 12q-.8-.65-1.25-1.55T4 8.5V6H2.5V4h12v2H13v2.5q0 1.05-.45 1.95T11.3 12q.8.65 1.25 1.55T13 15.5V18h1.5v2zm17 0L16 16.5l1.425-1.4l1.075 1.075V4h2v12.2l1.1-1.1l1.4 1.4zm-11-2");
}

</style>
