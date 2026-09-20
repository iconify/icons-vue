<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmd74ubuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-1-sharp" /></template>
<style>
.pmd74ubuk {
  fill: currentColor;
  d: path("M14 14.5h1v-9h-3v1h2zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>
