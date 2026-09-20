<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gop_bd_br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-hospital-outline-sharp" /></template>
<style>
.gop_bd_br {
  fill: currentColor;
  d: path("M10.5 17h3v-3.5H17v-3h-3.5V7h-3v3.5H7v3h3.5zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
