<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ytue87boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:diskusage" /></template>
<style>
.ytue87boh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.38 12.19a1.88 1.88 0 0 0-1.88 1.88V36.9a1.88 1.88 0 0 0 1.88 1.88h8.78l1.78-3.08h3.79v3.08H24l1.78-3.08h7.71l-10.92-13l-1.08-1.19l14.77-9.37ZM33.49 35.7l2.6 3.08h5.53a1.88 1.88 0 0 0 1.88-1.88V24.34H23.92m12.34-12.15l4.68-2.97v15.12");
}

</style>
