<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r31q4f_ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:csv-outline-sharp" /></template>
<style>
.r31q4f_ol {
  fill: currentColor;
  d: path("M5.327 14.692h3.385v-.884h-2.5v-3.616h2.5v-.884H5.327zm4.785 0h3.384v-3.111h-2.5v-1.389h2.5v-.884h-3.385v3.1h2.5v1.4h-2.5zm6.138 0h1.192L19 9.308h-.923l-1.23 4.258l-1.232-4.258h-.923zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
