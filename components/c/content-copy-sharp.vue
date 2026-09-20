<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srqqheb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:content-copy-sharp" /></template>
<style>
.srqqheb8i {
  fill: currentColor;
  d: path("M7.5 17V3h11v14zm-3 3V6.616h1V19h9.385v1z");
}

</style>
