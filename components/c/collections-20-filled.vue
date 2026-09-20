<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ipjt3li4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:collections-20-filled" /></template>
<style>
.ipjt3li4e {
  fill: currentColor;
  d: path("M15.5 7a2.5 2.5 0 0 1 2.496 2.335l.005.164v6a2.5 2.5 0 0 1-2.336 2.495l-.164.005h-6a2.5 2.5 0 0 1-2.495-2.336l-.005-.164v-6a2.5 2.5 0 0 1 2.336-2.495L9.5 7zm-2.999 2a.5.5 0 0 0-.492.41l-.008.09V12H9.5l-.09.007a.5.5 0 0 0 0 .984l.09.008H12v2.5l.008.09a.5.5 0 0 0 .984 0L13 15.5V13h2.5l.09-.008a.5.5 0 0 0 0-.984L15.5 12H13V9.5l-.008-.09A.5.5 0 0 0 12.5 9m.162-5.306l.048.158l.575 2.147H9.001a3 3 0 0 0-2.995 2.824l-.005.176v5.348a2.5 2.5 0 0 1-2.31-1.683l-.052-.17l-1.553-5.795a2.5 2.5 0 0 1 1.61-3.015l.158-.047l5.795-1.553a2.5 2.5 0 0 1 2.957 1.458z");
}

</style>
