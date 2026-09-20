<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd2jcrbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:jamboard-kiosk-sharp" /></template>
<style>
.pd2jcrbpn {
  fill: currentColor;
  d: path("M7 20v-1h4.5v-3H3V4h18v12h-8.5v3H17v1z");
}

</style>
