<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulcx2tekk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edgesensor-low-outline-sharp" /></template>
<style>
.ulcx2tekk {
  fill: currentColor;
  d: path("M3 14V7h2v7zm16 3v-7h2v7zM6 21V3h12v18zm10-2V5H8v14zM12.713 7.713Q13 7.425 13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8t.713-.288M8 5v14z");
}

</style>
