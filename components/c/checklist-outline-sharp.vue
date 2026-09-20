<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvis35quz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:checklist-outline-sharp" /></template>
<style>
.rvis35quz {
  fill: currentColor;
  d: path("M5.839 17.904L3 15.066l.689-.689l2.125 2.125l4.25-4.25l.688.714zm0-7.231L3 7.835l.689-.689l2.125 2.125l4.25-4.25l.688.714zm7.18 5.442v-1h8v1zm0-7.23v-1h8v1z");
}

</style>
