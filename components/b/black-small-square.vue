<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ddovr0uap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:black-small-square" /></template>
<style>
.ddovr0uap {
  fill: var(--svg-color--333, #333);
  d: path("M16 16h32v32H16z");
}

</style>
