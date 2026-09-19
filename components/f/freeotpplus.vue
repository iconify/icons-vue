<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z33raibgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freeotpplus" /></template>
<style>
.z33raibgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5L7.11 14.25v19.5L24 43.5l16.89-9.75v-19.5ZM7.11 14.25L24 24m0 19.5V24m16.89-9.75L24 24M38.44 4.5v4.77m2.38-2.38h-4.77");
}

</style>
