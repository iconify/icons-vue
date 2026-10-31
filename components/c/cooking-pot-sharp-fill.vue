<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="klqf0826j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cooking-pot-sharp-fill" /></template>
<style>
.klqf0826j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.988 10.0001C3.992 10 3.996 10 4 10L20 10C20.004 10 20.008 10 20.012 10.0001L23 10.0001L23 12.0001L21 12.0001L21 21C21 21.5523 20.5523 22 20 22L4 22C3.4477 22 3 21.5523 3 21L3 12.0001L1 12.0001L1 10.0001L3.988 10.0001ZM7 6.0001L7 3C7 2.4477 7.4477 2 8 2L16 2C16.5523 2 17 2.4477 17 3L17 6.0001L21 6.0001L21 8.0001L3 8.0001L3 6.0001L7 6.0001Z");
}

</style>
