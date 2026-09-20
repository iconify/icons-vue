<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfd0e_j7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:holiday-village-sharp" /></template>
<style>
.jfd0e_j7o {
  fill: currentColor;
  d: path("M2 20V10l6-6l6 6v10H9v-5H7v5zm5-7h2v-2H7zm9 7V9.175L10.825 4h2.825L18 8.35V20zm4 0V7.525L16.475 4H19.3L22 6.7V20z");
}

</style>
