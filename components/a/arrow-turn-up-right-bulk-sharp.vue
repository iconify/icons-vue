<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwj2bfh8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-up-right-bulk-sharp" /></template>
<style>
.fwj2bfh8m {
  fill: currentColor;
  d: path("M14.586 9H8v12a1 1 0 0 1-2 0V8a1 1 0 0 1 1-1h7.586l-3.293-3.293a.999.999 0 1 1 1.414-1.414l5 5a1 1 0 0 1 0 1.414l-5 5a.999.999 0 1 1-1.414-1.414Z");
}

</style>
