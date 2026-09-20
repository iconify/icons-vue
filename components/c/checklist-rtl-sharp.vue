<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0ga-wu0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:checklist-rtl-sharp" /></template>
<style>
.m0ga-wu0d {
  fill: currentColor;
  d: path("m16.106 17.904l-2.839-2.838l.689-.689l2.125 2.125l4.25-4.25l.688.714zm0-7.231l-2.839-2.838l.689-.689l2.125 2.125l4.25-4.25l.688.714zM3 16.116v-1h8v1zm0-7.231v-1h8v1z");
}

</style>
