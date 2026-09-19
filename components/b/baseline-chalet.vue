<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-0ehc0pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-chalet" /></template>
<style>
.i-0ehc0pd {
  fill: currentColor;
  d: path("m10 7.5l7.5 7.5l-1.41 1.41L15 15.33V20h-4v-5H9v5H5v-4.67l-1.09 1.09L2.5 15zm12-1h-1.19l.75-.75l-.71-.71l-1.46 1.46h-.89v-.89l1.45-1.45l-.71-.71l-.74.74V3h-1v1.19l-.75-.75l-.71.71l1.45 1.45v.9h-.89l-1.45-1.45l-.71.71l.75.75H14v1h1.19l-.75.75l.71.71l1.45-1.45h.89v.89l-1.45 1.45l.71.71l.75-.75V11h1V9.81l.75.75l.71-.71l-1.46-1.46V7.5h.89l1.45 1.45l.71-.71l-.74-.74H22z");
}

</style>
