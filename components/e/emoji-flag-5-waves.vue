<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zmt-1qbbt"/><path class="svd6j7bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-flag-5-waves" /></template>
<style>
.svd6j7bwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 31.122c-2.459-.636-4.875-1.272-9.75-1.272c-8.478 0-11.022 2.544-19.5 2.544c-4.875 0-7.334-.636-9.75-1.272m39-14.244c-2.459-.636-4.875-1.271-9.75-1.271c-8.478 0-11.022 2.543-19.5 2.543c-4.875 0-7.334-.636-9.75-1.272m39 4.748c-2.459-.636-4.875-1.272-9.75-1.272c-8.478 0-11.022 2.544-19.5 2.544c-4.875 0-7.334-.636-9.75-1.272m39 4.748c-2.459-.636-4.875-1.272-9.75-1.272c-8.478 0-11.022 2.544-19.5 2.544c-4.875 0-7.334-.636-9.75-1.272");
}

.zmt-1qbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 35.87V12.13c2.416.636 4.875 1.272 9.75 1.272c8.478 0 11.022-2.543 19.5-2.543c4.875 0 7.291.636 9.75 1.271v23.74c-2.459-.636-4.875-1.272-9.75-1.272c-8.478 0-11.022 2.543-19.5 2.543c-4.875 0-7.334-.636-9.75-1.272Z");
}

</style>
