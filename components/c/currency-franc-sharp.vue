<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifqa-hi3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:currency-franc-sharp" /></template>
<style>
.ifqa-hi3d {
  fill: currentColor;
  d: path("M7.692 20v-3h-2v-1h2V4h9.616v1H8.692v6.308h7.616v1H8.692V16H12.5v1H8.692v3z");
}

</style>
