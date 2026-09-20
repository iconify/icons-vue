<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d98_h4w4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-sharp" /></template>
<style>
.d98_h4w4a {
  fill: currentColor;
  d: path("M9.154 13.692h8.692l-2.758-3.653l-2.453 3.077l-1.589-1.885zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>
