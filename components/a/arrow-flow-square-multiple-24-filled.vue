<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udjxdxkvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-square-multiple-24-filled" /></template>
<style>
.udjxdxkvi {
  fill: currentColor;
  d: path("M18.998 6.01a3.25 3.25 0 0 1 3 3.24v6.5a6.25 6.25 0 0 1-6.25 6.25h-6.5a3.25 3.25 0 0 1-3.24-3h8.74a4.25 4.25 0 0 0 4.25-4.25zM14.75 2A3.25 3.25 0 0 1 18 5.25v9.5A3.25 3.25 0 0 1 14.75 18h-9.5A3.25 3.25 0 0 1 2 14.75v-4.615A2.5 2.5 0 0 0 5.135 8.5H5.6a3.43 3.43 0 0 1 2.79 1.436A4.93 4.93 0 0 0 12.4 12h1.04l-1.72 1.72a.75.75 0 1 0 1.06 1.06l3-3a.75.75 0 0 0 0-1.06l-3-3a.75.75 0 1 0-1.06 1.06l1.72 1.72H12.4a3.43 3.43 0 0 1-2.79-1.436A4.93 4.93 0 0 0 5.6 7h-.465A2.5 2.5 0 0 0 2 5.364V5.25A3.25 3.25 0 0 1 5.25 2zm-12 4.75a1 1 0 1 1 0 2a1 1 0 0 1 0-2");
}

</style>
