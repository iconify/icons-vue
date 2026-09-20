<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k37ci7kfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-tote-sharp" /></template>
<style>
.k37ci7kfb {
  fill: currentColor;
  d: path("m14.525 13.5l4-4l-1.4-1.425l-1.6 1.575V5.5h-2v4.15l-1.6-1.575l-1.4 1.425ZM3.75 22.125L1.9 7.2l3.125-.35V19h13.45v1.275ZM7.025 17V2h15v15Z");
}

</style>
