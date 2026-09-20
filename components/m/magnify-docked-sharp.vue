<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5bovl8ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:magnify-docked-sharp" /></template>
<style>
.f5bovl8ga {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-5h16V6H4zm10-1.5h2v-2h2v-2h-2v-2h-2v2h-2v2h2z");
}

</style>
