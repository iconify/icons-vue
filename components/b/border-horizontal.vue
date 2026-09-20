<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou67ikz8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:border-horizontal" /></template>
<style>
.ou67ikz8b {
  fill: currentColor;
  d: path("M3 21v-2h2v2zm0-4v-2h2v2zm0-4v-2h18v2zm0-4V7h2v2zm0-4V3h2v2zm4 16v-2h2v2zM7 5V3h2v2zm4 16v-2h2v2zm0-4v-2h2v2zm0-8V7h2v2zm0-4V3h2v2zm4 16v-2h2v2zm0-16V3h2v2zm4 16v-2h2v2zm0-4v-2h2v2zm0-8V7h2v2zm0-4V3h2v2z");
}

</style>
