<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsx4tdbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-days-sharp" /></template>
<style>
.hsx4tdbgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 5h16v16H4Zm4-2v2m8-2v2M4 9h16M8 13h.01M8 17h.01M12 13h.01M12 17h.01M16 13h.01M16 17h.01");
}

</style>
