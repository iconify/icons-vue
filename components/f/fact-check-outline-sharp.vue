<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cthp-cp2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fact-check-outline-sharp" /></template>
<style>
.cthp-cp2l {
  fill: currentColor;
  d: path("M5.5 16.5h4v-1h-4zm9.05-2.211l4.238-4.239l-.713-.714l-3.525 3.55l-1.425-1.424l-.688.713zM5.5 12.5h4v-1h-4zm0-4h4v-1h-4zM3 20V4h18v16zm1-1h16V5H4zm0 0V5z");
}

</style>
