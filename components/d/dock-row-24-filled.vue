<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5sqjdbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dock-row-24-filled" /></template>
<style>
.c5sqjdbis {
  fill: currentColor;
  d: path("M20.25 12.03c.966 0 1.75.783 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 16 16.28v-2.5c0-.967.784-1.75 1.75-1.75zm-14 0c.966 0 1.75.783 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 2 16.28v-2.5c0-.967.784-1.75 1.75-1.75zm7 0c.966 0 1.75.783 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 16.28v-2.5c0-.967.784-1.75 1.75-1.75zm0-7c.966 0 1.75.783 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 9.28v-2.5c0-.967.784-1.75 1.75-1.75zm7 0c.966 0 1.75.783 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 16 9.28v-2.5c0-.967.784-1.75 1.75-1.75zm-14 0c.966 0 1.75.783 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 2 9.28v-2.5a1.75 1.75 0 0 1 1.606-1.745l.144-.006z");
}

</style>
