<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-vgycc8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:horizontal-rule-outline-rounded" /></template>
<style>
.s-vgycc8v {
  fill: currentColor;
  d: path("M5 13q-.425 0-.712-.288T4 12t.288-.712T5 11h14q.425 0 .713.288T20 12t-.288.713T19 13z");
}

</style>
