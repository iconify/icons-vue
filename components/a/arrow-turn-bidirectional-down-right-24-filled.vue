<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn-u7vvog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-bidirectional-down-right-24-filled" /></template>
<style>
.tn-u7vvog {
  fill: currentColor;
  d: path("M17.707 3.293a1 1 0 1 0-1.414 1.414l2.294 2.294H11.5a4.5 4.5 0 0 0-4.5 4.5v7.086l-2.293-2.293a1 1 0 1 0-1.414 1.415l4 4a1 1 0 0 0 1.415 0l4-4a1 1 0 0 0-1.415-1.415L9 18.587v-7.086a2.5 2.5 0 0 1 2.5-2.5h7.086l-2.293 2.293a1 1 0 1 0 1.414 1.414l4-4a1 1 0 0 0 0-1.414z");
}

</style>
