<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am8l84brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:comic-bubble-sharp" /></template>
<style>
.am8l84brn {
  fill: currentColor;
  d: path("M11 1.1L13.9 4H18v4.1l2.9 2.9l-2.9 2.9l2.875 5.65l-1.325 1.325L13.9 18L11 20.9L8.1 18H4v-4.1L1.1 11L4 8.1V4h4.1z");
}

</style>
