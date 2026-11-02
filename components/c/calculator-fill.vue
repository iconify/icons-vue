<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdfn5bbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calculator-fill" /></template>
<style>
.kdfn5bbjx {
  fill: currentColor;
  d: path("M6 2h12a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m2 5a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Zm.01 4H8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m4 0H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M17 16v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m-9-1a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4.01 0H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
