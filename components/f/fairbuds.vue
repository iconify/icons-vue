<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ef21ymror"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fairbuds" /></template>
<style>
.ef21ymror {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.249 15.636v16.728M24 4.5v39m5.751-29.441V33.94m5.752-14.003v8.125m-28.756-8.34v8.555m5.751-15.102v21.65M41.254 22.04v3.92");
}

</style>
