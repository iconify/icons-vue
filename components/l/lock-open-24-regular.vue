<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u31xefpyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-open-24-regular" /></template>
<style>
.u31xefpyu {
  fill: currentColor;
  d: path("M18.75 1a4.75 4.75 0 0 1 4.75 4.75v.5a.75.75 0 0 1-1.5 0v-.5a3.25 3.25 0 0 0-6.5 0V8h1.25A3.25 3.25 0 0 1 20 11.25v7.5A3.25 3.25 0 0 1 16.75 22h-9.5A3.25 3.25 0 0 1 4 18.75v-7.5A3.25 3.25 0 0 1 7.25 8H14V5.75A4.75 4.75 0 0 1 18.75 1M7.25 9.5a1.75 1.75 0 0 0-1.75 1.75v7.5c0 .966.784 1.75 1.75 1.75h9.5a1.75 1.75 0 0 0 1.75-1.75v-7.5a1.75 1.75 0 0 0-1.75-1.75zM12 13.75a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
