<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x59723bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:curtains-closed-outline-sharp" /></template>
<style>
.x59723bpz {
  fill: currentColor;
  d: path("M2 21v-2h2V3h16v16h2v2zm4-2h3V5H6zm5 0h2V5h-2zm4 0h3V5h-3zm-9 0V5zm12 0V5z");
}

</style>
