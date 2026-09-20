<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3vbmlovz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-alert-outline" /></template>
<style>
.m3vbmlovz {
  fill: currentColor;
  d: path("M11 14h2V8h-2zm1 4q.425 0 .713-.288T13 17t-.288-.712T12 16t-.712.288T11 17t.288.713T12 18m-4 4q-.425 0-.712-.288T7 21V5q0-.425.288-.712T8 4h2V2h4v2h2q.425 0 .713.288T17 5v16q0 .425-.288.713T16 22zm1-2h6V6H9zm0 0h6z");
}

</style>
