<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhs9ccc9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-arrow-outline" /></template>
<style>
.hhs9ccc9u {
  fill: currentColor;
  d: path("M11 19v-6H2v-2h9V5l11 7zm2-3.65L18.275 12L13 8.65zM13 12");
}

</style>
