<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="txoqlmbaj"/><path class="t8u1edbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bdv" /></template>
<style>
.t8u1edbok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.067 14.515L22.16 42.5l15.415-8.23L22.848 6.465a1.814 1.814 0 0 0-2.42-.77l-12.58 6.34a1.814 1.814 0 0 0-.78 2.48");
}

.txoqlmbaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.16 42.5l15.415-8.23l3.56-26.758c.172-1.289-1.195-2.225-2.335-1.599l-12.842 7.055a2.6 2.6 0 0 0-1.34 2.05z");
}

</style>
