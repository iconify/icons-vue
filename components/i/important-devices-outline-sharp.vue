<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trp-8m0cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:important-devices-outline-sharp" /></template>
<style>
.trp-8m0cm {
  fill: currentColor;
  d: path("M16 21v-9.95h6V21zm1-2h4v-5.95h-4zm-9 2v-2h2v-2H2V3h18v6.05h-2V5H4v10h10v2h-2v2h2v2zm.7-7.25L11 12l2.3 1.75l-.85-2.85l2.3-1.85H11.9l-.9-2.8l-.9 2.8H7.25l2.3 1.85zM11 10");
}

</style>
