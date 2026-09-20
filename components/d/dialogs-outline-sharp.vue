<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0x0byb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dialogs-outline-sharp" /></template>
<style>
.t0x0byb1x {
  fill: currentColor;
  d: path("M8 16h8V8H8zm-5 5V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
