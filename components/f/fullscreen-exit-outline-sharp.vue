<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5m0xac4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fullscreen-exit-outline-sharp" /></template>
<style>
.g5m0xac4x {
  fill: currentColor;
  d: path("M6 21v-3H3v-2h5v5zm10 0v-5h5v2h-3v3zM3 8V6h3V3h2v5zm13 0V3h2v3h3v2z");
}

</style>
