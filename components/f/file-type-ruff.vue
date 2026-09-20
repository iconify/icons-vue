<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o-r8t4bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ruff" /></template>
<style>
.o-r8t4bal {
  fill: var(--svg-color--d7ff64, #d7ff64);
  d: path("M30 4.8A2.8 2.8 0 0 0 27.2 2H2v28h12.88v-8.4h2.24V30H30V19.36h-5.6v-2.24h2.8a2.8 2.8 0 0 0 2.8-2.8zM19.36 14.88h-6.72v-2.24h6.72z");
}

</style>
