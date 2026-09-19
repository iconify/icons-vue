<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nd02x4lvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:blue-circle" /></template>
<style>
.nd02x4lvz {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M57.55 14.449c9.697 14.11 6.111 33.406-8 43.1c-14.11 9.697-33.407 6.112-43.1-8c-9.687-14.11-6.111-33.408 8-43.1c14.11-9.687 33.406-6.109 43.1 8");
}

</style>
