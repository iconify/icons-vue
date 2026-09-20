<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6xk1-mwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hourglass-arrow-up-outline-sharp" /></template>
<style>
.e6xk1-mwp {
  fill: currentColor;
  d: path("M8.5 11q1.05 0 1.775-.725T11 8.5V6H6v2.5q0 1.05.725 1.775T8.5 11M6 18h5v-2.5q0-1.05-.725-1.775T8.5 13t-1.775.725T6 15.5zm-3.5 2v-2H4v-2.5q0-1.05.45-1.95T5.7 12q-.8-.65-1.25-1.55T4 8.5V6H2.5V4h12v2H13v2.5q0 1.05-.45 1.95T11.3 12q.8.65 1.25 1.55T13 15.5V18h1.5v2zm16 0V7.8l-1.1 1.1L16 7.5L19.5 4L23 7.5l-1.425 1.4L20.5 7.825V20zm-10-2");
}

</style>
