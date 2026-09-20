<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmhtoobbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:high-density" /></template>
<style>
.zmhtoobbq {
  fill: currentColor;
  d: path("M3 17V3h14v14zm0 4v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2z");
}

</style>
