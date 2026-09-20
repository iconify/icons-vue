<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="lwym06acw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-28-regular" /></template>
<style>
.lwym06acw {
  fill: currentColor;
  d: path("M14 2c6.627 0 12 5.373 12 12s-5.373 12-12 12c-2.036 0-3.956-.507-5.637-1.403l-4.77 1.356a1.25 1.25 0 0 1-1.544-1.545l1.356-4.768A11.95 11.95 0 0 1 2 14C2 7.373 7.372 2 14 2m0 1.5C8.2 3.5 3.5 8.201 3.5 14c0 1.884.495 3.65 1.363 5.178a.75.75 0 0 1 .07.575l-1.318 4.634l4.635-1.318a.75.75 0 0 1 .575.07A10.45 10.45 0 0 0 14 24.5c5.799 0 10.5-4.701 10.5-10.5S19.799 3.5 14 3.5m4.47 6.72a.75.75 0 0 1 1.06 1.06l-6.5 6.5a.75.75 0 0 1-1.06 0l-3.5-3.5a.75.75 0 0 1 1.06-1.06l2.97 2.97z");
}

</style>
