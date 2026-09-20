<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rdv37fe1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-left-down-20-filled" /></template>
<style>
.rdv37fe1x {
  fill: currentColor;
  d: path("M3.22 10.72a.75.75 0 0 0 0 1.06l4 4a.75.75 0 0 0 1.06 0l4-4a.75.75 0 1 0-1.06-1.06L8.5 13.44V7A1.5 1.5 0 0 1 10 5.5h6.25a.75.75 0 0 0 0-1.5H10a3 3 0 0 0-3 3v6.44l-2.72-2.72a.75.75 0 0 0-1.06 0");
}

</style>
