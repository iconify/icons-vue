<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p38njhtgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-flex-start-outline" /></template>
<style>
.p38njhtgy {
  fill: currentColor;
  d: path("M3 4V3h18v1zm8 16V7h2v13z");
}

</style>
