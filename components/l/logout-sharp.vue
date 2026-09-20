<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7a4dwbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:logout-sharp" /></template>
<style>
.g7a4dwbam {
  fill: currentColor;
  d: path("M4 20V4h8.02v1H5v14h7.02v1zm12.462-4.461l-.702-.72l2.319-2.319H9.192v-1h8.887l-2.32-2.32l.702-.718L20 12z");
}

</style>
