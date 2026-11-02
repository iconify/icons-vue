<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxcc6fbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-horizontal-fill-sharp" /></template>
<style>
.vxcc6fbgw {
  fill: currentColor;
  d: path("M11 7V5a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0m-7.293-.707l5 5a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 2 17V7a1.002 1.002 0 0 1 1.707-.707m16.586 0A1 1 0 0 1 22 7v10a1.002 1.002 0 0 1-1.707.707l-5-5a1 1 0 0 1 0-1.414ZM13 13a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm0 6a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
