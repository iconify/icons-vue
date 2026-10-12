<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqzocqbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-right-left-3" /></template>
<style>
.nqzocqbgi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 17L2.7396 17M6.8947 12L2.1367 16.6759C1.9544 16.8549 1.9544 17.1451 2.1367 17.3241L6.8947 22M11 7L21.2604 7M17.1053 12L21.8633 7.3241C22.0456 7.1451 22.0456 6.8549 21.8633 6.6759L17.1053 2");
}

</style>
