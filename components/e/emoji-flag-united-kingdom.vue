<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rvlpnmbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-flag-united-kingdom" /></template>
<style>
.rvlpnmbem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 36.12l39-24.24m-39 0l39 24.24m0 0V12.38m-39-.5v23.74m39 .5c-2.459-.636-4.875-1.272-9.75-1.272c-8.478 0-11.022 2.543-19.5 2.543c-4.875 0-7.334-.636-9.75-1.271m39-24.24c-2.459-.636-4.875-1.271-9.75-1.271c-8.478 0-11.022 2.543-19.5 2.543c-4.875 0-7.334-.636-9.75-1.272m39 11.87c-2.459-.636-4.875-1.272-9.75-1.272c-8.478 0-11.022 2.544-19.5 2.544c-4.875 0-7.334-.636-9.75-1.272M24 35.62V11.88");
}

</style>
