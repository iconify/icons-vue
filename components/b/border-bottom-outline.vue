<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n765p86ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:border-bottom-outline" /></template>
<style>
.n765p86ft {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2zm4 8v-2h2v2zm0-8V3h2v2zm4 12v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2zm4 8v-2h2v2zm0-8V3h2v2zm4 12v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2z");
}

</style>
