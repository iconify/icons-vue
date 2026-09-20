<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rja64pb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:currency-ngn-thin" /></template>
<style>
.rja64pb9z {
  fill: currentColor;
  d: path("M216 140h-20v-24h20a4 4 0 0 0 0-8h-20V46a4 4 0 0 0-8 0v62h-70.54L67.15 43.54A4 4 0 0 0 60 46v62H40a4 4 0 0 0 0 8h20v24H40a4 4 0 0 0 0 8h20v62a4 4 0 0 0 8 0v-62h70.54l50.31 64.46A4 4 0 0 0 192 214a3.9 3.9 0 0 0 1.3-.22A4 4 0 0 0 196 210v-62h20a4 4 0 0 0 0-8m-28-24v24h-45.56l-18.73-24ZM68 57.63L107.32 108H68ZM68 140v-24h45.56l18.73 24Zm120 58.37L148.68 148H188Z");
}

</style>
