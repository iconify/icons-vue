<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv06-zbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:co2-sharp" /></template>
<style>
.dv06-zbwn {
  fill: currentColor;
  d: path("M10 15V9h5v6zm1.5-1.5h2v-3h-2zM3 15V9h5v2H6.5v-.5h-2v3h2V13H8v2zm14 3v-3.5h3v-1h-3V12h4.5v3.5h-3v1h3V18z");
}

</style>
