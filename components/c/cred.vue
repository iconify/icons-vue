<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dbr48wboa"/><path class="duk-i5bqa"/><path class="gpwrzpbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cred" /></template>
<style>
.dbr48wboa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.013 33.553L24.027 43.5l-17.04-9.947V4.5h34.026z");
}

.duk-i5bqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.651 21.872v9.232L24.02 38.5l-12.671-7.396V14.5H24m-8.355-5h21.006v7.715");
}

.gpwrzpbny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.485 29.71l-6.472 3.79l-8.302-4.846v-6.056");
}

</style>
