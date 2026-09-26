<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_sk32p-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-right-duotone" /></template>
<style>
.j_sk32p-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.7413 12.456L6.7841 18.9273C6.43652 19.1326 6 18.8787 6 18.4713L6 5.52868C6 5.12126 6.43651 4.86742 6.7841 5.0727L17.7413 11.544C18.0862 11.7477 18.0862 12.2523 17.7413 12.456Z");
}

</style>
