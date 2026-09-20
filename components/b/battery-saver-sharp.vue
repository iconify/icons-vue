<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cninoobpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-saver-sharp" /></template>
<style>
.cninoobpr {
  fill: currentColor;
  d: path("M16 22v-3h-3v-2h3v-3h2v3h3v2h-3v3zm-9 0V4h3V2h4v2h3v8q-2.5.025-4.25 1.763T11 18q0 1.15.4 2.175T12.525 22z");
}

</style>
