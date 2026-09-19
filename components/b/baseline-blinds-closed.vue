<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn3w0p46b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-blinds-closed" /></template>
<style>
.rn3w0p46b {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h11.25c0 .97.78 1.75 1.75 1.75s1.75-.78 1.75-1.75H22v-2zm-2-8h-2V9h2zm-4 0H6V9h8zm0 2v2H6v-2zm2 0h2v2h-2zm2-6h-2V5h2zm-4-2v2H6V5zM6 19v-2h8v2zm10 0v-2h2v2z");
}

</style>
