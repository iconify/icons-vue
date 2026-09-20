<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_fde_bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:deskphone-outline-sharp" /></template>
<style>
.x_fde_bai {
  fill: currentColor;
  d: path("M17 19h2V5h-2zM6 14h2v-2H6zm0 3h2v-2H6zm0-6h8V7H6zm3 3h2v-2H9zm0 3h2v-2H9zm3-3h2v-2h-2zm0 3h2v-2h-2zm3 1V6H5v12zM3 20V4h12V3h6v18h-6v-1zm2-2V6z");
}

</style>
