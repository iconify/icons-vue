<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezp60hblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:desk" /></template>
<style>
.ezp60hblu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 12L22 12M7 8L7 12L4 12L4 22M20 12L20 22M20 19L4 19M7 8L4.6404 8C4.3151 8 4.0764 7.6943 4.1553 7.3787L5.4053 2.3787C5.461 2.1562 5.661 2 5.8904 2L8.1096 2C8.339 2 8.539 2.1562 8.5947 2.3787L9.8447 7.3787C9.9236 7.6943 9.6849 8 9.3596 8Z");
}

</style>
