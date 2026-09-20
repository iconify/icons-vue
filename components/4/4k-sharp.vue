<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h93c6jwnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:4k-sharp" /></template>
<style>
.h93c6jwnk {
  fill: currentColor;
  d: path("M13 15h1.5v-2.25L16.25 15H18l-2.25-3L18 9h-1.75l-1.75 2.25V9H13zm-3.5 0H11v-1.5h1V12h-1V9H9.5v3H8V9H6.5v4.5h3zM3 21V3h18v18z");
}

</style>
