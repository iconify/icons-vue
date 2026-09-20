<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erjg5db5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:google-wifi-outline-sharp" /></template>
<style>
.erjg5db5w {
  fill: currentColor;
  d: path("M4.639 11h14.703l-.313-5H4.97zm-.068 1l-.325 5.154h15.508L19.41 12zm1.121 7l-.267-.846H3.173L4.038 5h15.924l.865 13.154h-2.252l-.267.846z");
}

</style>
