<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wafypqiaw"/><path class="joqitnbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-csv" /></template>
<style>
.joqitnbaf {
  fill: var(--svg-color--73b568, #73b568);
  d: path("M8.125 15.097h13.076v1.75H8.125zm0 9.342h9.762v1.75H8.125zm0-4.676h15.75v1.75H8.125zm0-9.533h15.75v1.75H8.125z");
}

.wafypqiaw {
  fill: var(--svg-color--91d290, #91d290);
  d: path("M22.038 2H6.375a1.755 1.755 0 0 0-1.75 1.75v24.5A1.755 1.755 0 0 0 6.375 30h19.25a1.755 1.755 0 0 0 1.75-1.75V6.856Zm.525 2.844l1.663 1.531h-1.663ZM6.375 28.25V3.75h14.438v4.375h4.813V28.25Z");
}

</style>
