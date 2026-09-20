<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh8w2rbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:border-vertical-outline" /></template>
<style>
.hh8w2rbbk {
  fill: currentColor;
  d: path("M3 21v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2zm4 16v-2h2v2zm0-8v-2h2v2zm0-8V3h2v2zm4 16V3h2v18zm4 0v-2h2v2zm0-8v-2h2v2zm0-8V3h2v2zm4 16v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2z");
}

</style>
