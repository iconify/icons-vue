<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp580qb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-desktop-24-regular" /></template>
<style>
.lp580qb2h {
  fill: currentColor;
  d: path("M22 13a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-3v1.5h.25a.75.75 0 0 1 .746.824l.004.051c0 .276-.349.625-.625.625h-3.75c-.276 0-.625-.349-.625-.625q0-.026.004-.05L15 22.25a.75.75 0 0 1 .75-.75H16V20h-3a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1zM12 4a6 6 0 0 1 5.92 5.02A4.5 4.5 0 0 1 21.744 12h-1.65a3 3 0 0 0-2.594-1.5h-.256a.75.75 0 0 1-.749-.715a4.5 4.5 0 0 0-8.99 0a.75.75 0 0 1-.75.715H6.5a3 3 0 1 0 0 6H11V18H6.5a4.5 4.5 0 0 1-.42-8.98A6 6 0 0 1 12 4");
}

</style>
