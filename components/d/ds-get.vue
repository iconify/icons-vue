<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mw3wh8btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ds-get" /></template>
<style>
.mw3wh8btr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.947 19.718l9.173-.05V6.742l15.477.233V19.67h9.456L24.21 37.904zM5.5 41.26h37");
}

</style>
