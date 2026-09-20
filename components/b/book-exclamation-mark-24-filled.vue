<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwqzrg1rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-exclamation-mark-24-filled" /></template>
<style>
.pwqzrg1rb {
  fill: currentColor;
  d: path("M4 4.5v15A2.5 2.5 0 0 0 6.5 22h13.25a.75.75 0 0 0 0-1.5H6.5a1 1 0 0 1-1-1h14.25a.75.75 0 0 0 .75-.75V4.5A2.5 2.5 0 0 0 18 2H6.5A2.5 2.5 0 0 0 4 4.5m7.5 7.25v-5a.75.75 0 0 1 1.5 0v5a.75.75 0 0 1-1.5 0m1.75 2.75a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

</style>
