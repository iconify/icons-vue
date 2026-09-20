<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd7dqeltc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:document-scanner-outline-sharp" /></template>
<style>
.yd7dqeltc {
  fill: currentColor;
  d: path("M2 6V1h5v2H4v3zm18 0V3h-3V1h5v5zM2 23v-5h2v3h3v2zm15 0v-2h3v-3h2v5zM7 18h10V6H7zm-2 2V4h14v16zm4-10h6V8H9zm0 3h6v-2H9zm0 3h6v-2H9zm-2 2V6z");
}

</style>
