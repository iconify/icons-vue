<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffjmrdbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-text-snippet" /></template>
<style>
.ffjmrdbxr {
  fill: currentColor;
  d: path("m20.41 8.41l-4.83-4.83c-.37-.37-.88-.58-1.41-.58H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V9.83c0-.53-.21-1.04-.59-1.42M7 7h7v2H7zm10 10H7v-2h10zm0-4H7v-2h10z");
}

</style>
