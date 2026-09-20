<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrqzsqedq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-7-outline-sharp" /></template>
<style>
.jrqzsqedq {
  fill: currentColor;
  d: path("M11.154 14.5h1.038L16 6.5v-1h-5v1h3.962zM6.5 17V3h14v14zm1-1h12V4h-12zm-4 4V6.616h1V19h12.385v1zm4-4V4z");
}

</style>
