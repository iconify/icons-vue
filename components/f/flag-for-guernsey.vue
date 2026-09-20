<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="c-r52ubsi"/><path class="wqbbrsbfp"/><path class="bhd2s0b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-guernsey" /></template>
<style>
.bhd2s0b9l {
  fill: var(--svg-color--f9dd16, #f9dd16);
  d: path("M27.5 17H19V9.5l1-1h-4l1 1V17H8.5l-1-1v4l1-1H17v7.5l-1 1h4l-1-1V19h8.5l1 1v-4z");
}

.c-r52ubsi {
  fill: var(--svg-color--eee, #eee);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.wqbbrsbfp {
  fill: var(--svg-color--e8112d, #e8112d);
  d: path("M21 31h-6V21H0v-6h15V5h6v10h15v6H21z");
}

</style>
