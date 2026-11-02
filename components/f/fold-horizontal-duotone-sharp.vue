<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5ws0xb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fold-horizontal-duotone-sharp" /></template>
<style>
.s5ws0xb5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 15l3-3l-3-3m3 3H3m14-3l-3 3l3 3m-3-3h7m-9-8v4m0 8v4");
}

</style>
