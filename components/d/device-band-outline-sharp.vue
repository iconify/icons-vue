<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcl-y3b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:device-band-outline-sharp" /></template>
<style>
.zcl-y3b7h {
  fill: currentColor;
  d: path("M8 22V9H7V6h1V2h8v4h1v3h-1v13zm2-13.5V20h4V8.5zm0-2h4V4h-4zm0 2h4zm0-2h4z");
}

</style>
