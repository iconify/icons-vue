<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b65e7mxlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:exposure-sharp" /></template>
<style>
.b65e7mxlk {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5zm9.808-1.308v-2h-2v-.884h2v-2h.884v2h2v.884h-2v2zm-8.5-9.5h4.384v-.884H6.308z");
}

</style>
