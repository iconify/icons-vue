<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j72486acb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-a-photo-outline" /></template>
<style>
.j72486acb {
  fill: currentColor;
  d: path("M3 21q-.825 0-1.412-.587T1 19V7q0-.825.588-1.412T3 5h3.15L8 3h6v2H8.875L7.05 7H3v12h16v-9h2v9q0 .825-.587 1.413T19 21zM19 7V5h-2V3h2V1h2v2h2v2h-2v2zm-8 10.5q1.875 0 3.188-1.312T15.5 13t-1.312-3.187T11 8.5T7.813 9.813T6.5 13t1.313 3.188T11 17.5m0-2q-1.05 0-1.775-.725T8.5 13t.725-1.775T11 10.5t1.775.725T13.5 13t-.725 1.775T11 15.5");
}

</style>
