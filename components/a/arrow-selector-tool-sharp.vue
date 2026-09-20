<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2ztuacic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-selector-tool-sharp" /></template>
<style>
.q2ztuacic {
  fill: currentColor;
  d: path("m13.467 20.154l-3.336-7.185l-3.4 4.743V3.5l11.154 8.77h-5.889l3.293 7.032z");
}

</style>
