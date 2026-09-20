<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="un0f1gbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-28-filled" /></template>
<style>
.un0f1gbje {
  fill: currentColor;
  d: path("M14 2c6.627 0 12 5.373 12 12s-5.373 12-12 12c-2.036 0-3.956-.507-5.637-1.403l-4.77 1.356a1.25 1.25 0 0 1-1.543-1.545l1.355-4.768A11.95 11.95 0 0 1 2 14C2 7.373 7.373 2 14 2m5.53 8.22a.75.75 0 0 0-1.06 0l-5.97 5.97l-2.97-2.97a.75.75 0 0 0-1.06 1.06l3.5 3.5a.75.75 0 0 0 1.06 0l6.5-6.5a.75.75 0 0 0 0-1.06");
}

</style>
