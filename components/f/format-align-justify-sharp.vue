<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu5_s-p_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-align-justify-sharp" /></template>
<style>
.nu5_s-p_d {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4v-2h18v2zm0-4v-2h18v2zm0-4V7h18v2zm0-4V3h18v2z");
}

</style>
