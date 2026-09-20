<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxr85w9pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:location-city-sharp" /></template>
<style>
.gxr85w9pv {
  fill: currentColor;
  d: path("M3 21V7h6V5l3-3l3 3v6h6v10zm2-2h2v-2H5zm0-4h2v-2H5zm0-4h2V9H5zm6 8h2v-2h-2zm0-4h2v-2h-2zm0-4h2V9h-2zm0-4h2V5h-2zm6 12h2v-2h-2zm0-4h2v-2h-2z");
}

</style>
