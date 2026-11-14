<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs_pegi8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:compositing" /></template>
<style>
.hs_pegi8b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 11.25H4q-2.25 0-2.25-2.25V4q0-2.25 2.25-2.25h8q2.25 0 2.25 2.25v2.25h.625q3.375 0 3.375 3.375v1.125h.625q3.375 0 3.375 3.375v2.75q0 3.375-3.375 3.375h-5.75q-3.375 0-3.375-3.375V15.75h-.625q-3.375 0-3.375-3.375zm0-1.5H4q-.75 0-.75-.75V4q0-.75.75-.75h8q.75 0 .75.75v2.25H9.125q-3.375 0-3.375 3.375z");
}

</style>
