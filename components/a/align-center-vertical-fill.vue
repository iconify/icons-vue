<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr6scdcse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-center-vertical-fill" /></template>
<style>
.vr6scdcse {
  fill: currentColor;
  d: path("M3 9V6a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v3Zm18 0h-8V8a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3ZM3 11h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 4h8v3a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Zm18 1a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-1h8Z");
}

</style>
