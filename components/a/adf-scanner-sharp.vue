<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssvpicc2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:adf-scanner-sharp" /></template>
<style>
.ssvpicc2m {
  fill: currentColor;
  d: path("M2 20v-8h4V4h12v8h4v8zm6-8h8V6H8zm10 5q.425 0 .713-.288T19 16t-.288-.712T18 15t-.712.288T17 16t.288.713T18 17");
}

</style>
