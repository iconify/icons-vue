<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy4hdkb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:air-conditioner-fill" /></template>
<style>
.oy4hdkb6f {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm5 2a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2Zm1.685 9.557a4 4 0 0 1-.857 1.271A3.98 3.98 0 0 1 5 19a1 1 0 0 1 0-2c.533 0 1.039-.207 1.414-.586c.377-.377.588-.881.586-1.414a1 1 0 0 1 2 0a4 4 0 0 1-.315 1.557M11 21v-6a1 1 0 0 1 2 0v6a1 1 0 0 1-2 0m6.157-5.222A2 2 0 0 0 19 17a1 1 0 0 1 0 2a3.98 3.98 0 0 1-2.828-1.172a4 4 0 0 1-.857-1.271A4 4 0 0 1 15 15a1 1 0 0 1 2 0c-.001.267.052.532.157.778");
}

</style>
