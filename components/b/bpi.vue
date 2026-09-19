<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cd8xo184i"/><path class="paaswnbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bpi" /></template>
<style>
.cd8xo184i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-6 14.447v8.106");
}

.paaswnbue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 28.053v-8.106h2.634c1.52 0 2.735 1.216 2.735 2.736s-1.215 2.736-2.735 2.736H24M18.844 24c1.114 0 2.026.912 2.026 2.026s-.912 2.027-2.027 2.027H15.5v-8.106h3.343c1.115 0 2.027.912 2.027 2.026S19.958 24 18.843 24Zm-.001 0H15.5");
}

</style>
