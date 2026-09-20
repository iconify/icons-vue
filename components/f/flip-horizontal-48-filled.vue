<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lg6y-04za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flip-horizontal-48-filled" /></template>
<style>
.lg6y-04za {
  fill: currentColor;
  d: path("M43.761 39.312A1.5 1.5 0 0 1 42.5 40h-15a1.5 1.5 0 0 1-1.5-1.5v-33a1.5 1.5 0 0 1 2.866-.62l15 33a1.5 1.5 0 0 1-.105 1.432M29 12.425V37h11.17zM5 40a1 1 0 0 1-.905-1.425l16-34A1 1 0 0 1 22 5v34a1 1 0 0 1-1 1z");
}

</style>
