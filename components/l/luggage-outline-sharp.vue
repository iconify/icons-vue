<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvdihdbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:luggage-outline-sharp" /></template>
<style>
.kvdihdbsv {
  fill: currentColor;
  d: path("M7 21H5V6h4V2h6v4h4v15h-2q0 .425-.288.713T16 22t-.712-.288T15 21H9q0 .425-.288.713T8 22t-.712-.288T7 21m0-2h10V8H7zm2-1h2V9H9zm4 0h2V9h-2zM11 6h2V4h-2zm1 7.5");
}

</style>
