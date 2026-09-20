<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lpuoh1qbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:keep" /></template>
<style>
.lpuoh1qbl {
  fill: var(--svg-color--49dbb4, #49dbb4);
  fill-rule: evenodd;
  d: path("M12 21a8.997 8.997 0 0 0 9-9a9 9 0 0 0-9-9a9 9 0 0 0 0 18M9 8H8v2h.5v4H8v2h3.5v-2H11v-1.25h.595l1.01 1.25H12.5v2H16v-2h-.63l-1.74-2.01L15.315 10H16V8h-3.5v2h.15l-1.13 1.25H11V10h.5V8h-1v.5H10V8h-.5v.5H9z");
}

</style>
