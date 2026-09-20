<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u49m4k_ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-left-up-20-filled" /></template>
<style>
.u49m4k_ht {
  fill: currentColor;
  d: path("M3.22 9.28a.75.75 0 0 1 0-1.06l4-4a.75.75 0 0 1 1.06 0l4 4a.75.75 0 0 1-1.06 1.06L8.5 6.56V13a1.5 1.5 0 0 0 1.5 1.5h6.25a.75.75 0 0 1 0 1.5H10a3 3 0 0 1-3-3V6.56L4.28 9.28a.75.75 0 0 1-1.06 0");
}

</style>
