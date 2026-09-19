<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pfjqmo-ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:domestika" /></template>
<style>
.pfjqmo-ym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.331 10.51L4.5 23.39l10.4 14.1h18.29l10.31-14.1l-8.741-12.88l-10.826 14.416z");
}

</style>
