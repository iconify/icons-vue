<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rd1ln2vwt"/><path class="cday3e3-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dsphoto" /></template>
<style>
.cday3e3-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38 5.5H9c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.rd1ln2vwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.7 12.1c-2.5 0-4.5 2-4.5 4.5s2 4.5 4.5 4.5s4.5-2 4.5-4.5s-2.1-4.5-4.5-4.5M28 21l-7.2 7.2c-.3.3-.7.3-1 0l-1.4-1.4c-.3-.3-.7-.3-1 0l-7.8 7.8c-.3.3-.3.7 0 1c.1.1.3.2.5.2h27.8c.4 0 .7-.3.7-.7c0-.1 0-.3-.1-.4L29 21.1c-.2-.3-.7-.3-1-.1");
}

</style>
