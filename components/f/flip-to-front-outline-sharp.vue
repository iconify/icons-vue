<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_eje8bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flip-to-front-outline-sharp" /></template>
<style>
.k_eje8bju {
  fill: currentColor;
  d: path("M7 17V3h14v14zm2-2h10V5H9zm-6 6v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm4 12v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2z");
}

</style>
