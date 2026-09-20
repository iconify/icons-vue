<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0pto0bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:emergency-home-outline-sharp" /></template>
<style>
.v0pto0bgw {
  fill: currentColor;
  d: path("M11 13.375h2v-6.75h-2zm1.713 2.338Q13 15.425 13 15t-.288-.712T12 14t-.712.288T11 15t.288.713T12 16t.713-.288M12 22.8L1.2 12L12 1.2L22.8 12zm0-2.8l8-8l-8-8l-8 8zm0-8");
}

</style>
