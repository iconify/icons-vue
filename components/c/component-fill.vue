<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fph4z6l2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:component-fill" /></template>
<style>
.fph4z6l2q {
  fill: currentColor;
  d: path("M15.707 4.293a2.414 2.414 0 0 1 0 3.414l-2 2a2.414 2.414 0 0 1-3.414 0l-2-2a2.414 2.414 0 0 1 0-3.414l2-2a2.414 2.414 0 0 1 3.414 0Zm-6 6a2.414 2.414 0 0 1 0 3.414l-2 2a2.414 2.414 0 0 1-3.414 0l-2-2a2.414 2.414 0 0 1 0-3.414l2-2a2.414 2.414 0 0 1 3.414 0Zm12 0a2.414 2.414 0 0 1 0 3.414l-2 2a2.414 2.414 0 0 1-3.414 0l-2-2a2.414 2.414 0 0 1 0-3.414l2-2a2.414 2.414 0 0 1 3.414 0Zm-6 6a2.414 2.414 0 0 1 0 3.414l-2 2a2.414 2.414 0 0 1-3.414 0l-2-2a2.414 2.414 0 0 1 0-3.414l2-2a2.414 2.414 0 0 1 3.414 0Z");
}

</style>
