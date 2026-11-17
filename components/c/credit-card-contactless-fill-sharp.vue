<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4fh8gbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-contactless-fill-sharp" /></template>
<style>
.w4fh8gbtn {
  fill: currentColor;
  d: path("M2 19V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1M14.832 7.445a1 1 0 0 0-1.664 1.11a6.21 6.21 0 0 1 0 6.89a1 1 0 0 0 .277 1.387a1 1 0 0 0 1.387-.277a8.2 8.2 0 0 0 1.034-2.199a8.2 8.2 0 0 0-1.034-6.911m-2.42 3.234a4.6 4.6 0 0 0-.58-1.234a1 1 0 0 0-1.664 1.11a2.61 2.61 0 0 1 0 2.89a1 1 0 0 0 1.664 1.11a4.6 4.6 0 0 0 .58-3.876M8.01 11H8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
