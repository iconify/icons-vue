<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xhruk-bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:daihatsu" /></template>
<style>
.xhruk-bze {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.317 16.336H4.5l10.22 11.632l-2.384 3.696c18.345-3.53 32.17-6.548 31.107-10.015c-1.386-4.522-25.211-5.06-33.867-5.105l8.51 9.275l3.23-.75");
}

</style>
