<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxoabwbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-down" /></template>
<style>
.wxoabwbkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11.1093V6C4 3.79086 5.79086 2 8 2H16C18.2091 2 20 3.79086 20 6V11.1093M12 21.2307V11.1093M6.5 16.17L11.6314 21.8359C11.8296 22.0547 12.1704 22.0547 12.3686 21.8359L17.5 16.17");
}

</style>
