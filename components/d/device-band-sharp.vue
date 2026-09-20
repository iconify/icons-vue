<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfo2jdbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:device-band-sharp" /></template>
<style>
.tfo2jdbyw {
  fill: currentColor;
  d: path("M8 22V9H7V6h1V2h8v4h1v3h-1v13z");
}

</style>
