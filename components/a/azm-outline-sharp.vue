<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmq54xbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:azm-outline-sharp" /></template>
<style>
.cmq54xbuj {
  fill: currentColor;
  d: path("M10 23v-9H1L11 4h9v9zm6-8.825l2-2V6h-6.175l-2 2H16zm-4 4l2-2V10H7.825l-2 2H12z");
}

</style>
