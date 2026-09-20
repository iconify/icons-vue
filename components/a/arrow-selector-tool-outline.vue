<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npt5ajbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-selector-tool-outline" /></template>
<style>
.npt5ajbsp {
  fill: currentColor;
  d: path("m7.73 14.596l2.38-3.327h4.884L7.731 5.562zm5.737 5.558l-3.336-7.185l-3.4 4.743V3.5l11.154 8.77h-5.889l3.293 7.032zm-3.357-8.885");
}

</style>
