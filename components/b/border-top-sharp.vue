<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvxr7ytds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:border-top-sharp" /></template>
<style>
.bvxr7ytds {
  fill: currentColor;
  d: path("M3 21v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h18v2zm4 16v-2h2v2zm0-8v-2h2v2zm4 8v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm4 12v-2h2v2zm0-8v-2h2v2zm4 8v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2z");
}

</style>
