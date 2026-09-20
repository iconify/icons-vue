<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxi-_cbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-center-sharp" /></template>
<style>
.sxi-_cbaw {
  fill: currentColor;
  d: path("M2 13v-2h20v2zm5-3V7h10v3zm0 7v-3h10v3z");
}

</style>
