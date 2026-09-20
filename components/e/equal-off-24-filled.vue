<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drsjmy_3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:equal-off-24-filled" /></template>
<style>
.drsjmy_3h {
  fill: currentColor;
  d: path("M3.28 2.22a.75.75 0 1 0-1.06 1.06L6.94 8H4a1 1 0 0 0 0 2h4.94l4 4H4a1 1 0 1 0 0 2h10.94l5.78 5.78a.75.75 0 0 0 1.06-1.06zM20 14h-2.818l2 2H20a1 1 0 1 0 0-2m-8.818-6l2 2H20a1 1 0 1 0 0-2z");
}

</style>
