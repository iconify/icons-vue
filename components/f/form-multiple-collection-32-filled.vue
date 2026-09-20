<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vbve-4b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:form-multiple-collection-32-filled" /></template>
<style>
.vbve-4b4x {
  fill: currentColor;
  d: path("M25.5 11a4.5 4.5 0 0 1 4.5 4.5v10a4.5 4.5 0 0 1-4.5 4.5h-10a4.5 4.5 0 0 1-4.5-4.5v-10a4.5 4.5 0 0 1 4.5-4.5zM17 21a3 3 0 1 0 0 6a3 3 0 0 0 0-6m0 2a1 1 0 1 1 0 2a1 1 0 0 1 0-2m6 0a1 1 0 0 0 0 2h3a1 1 0 0 0 0-2zM14.996 2.154a4.5 4.5 0 0 1 5.512 3.182L21.623 9.5h-6.122a6 6 0 0 0-6 6v7.727a4.5 4.5 0 0 1-4.758-3.314l-2.589-9.66a4.5 4.5 0 0 1 3.183-5.51zM17 14a3 3 0 1 0 0 6a3 3 0 0 0 0-6m0 2a1 1 0 1 1 0 2a1 1 0 0 1 0-2m6 0a1 1 0 0 0 0 2h3a1 1 0 0 0 0-2z");
}

</style>
