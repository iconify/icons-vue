<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="iowhbcb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:door-arrow-right-28-filled" /></template>
<style>
.iowhbcb6j {
  fill: currentColor;
  d: path("M8 2a3 3 0 0 0-3 3v18a3 3 0 0 0 3 3h7.4A7.5 7.5 0 0 1 23 13.427V5a3 3 0 0 0-3-3zm1.5 13a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3M27 20.5a6.5 6.5 0 1 1-13 0a6.5 6.5 0 0 1 13 0M16.5 20a.5.5 0 0 0 0 1h6.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 .146-.351v-.006a.5.5 0 0 0-.146-.35l-3-3a.5.5 0 0 0-.708.707L23.293 20z");
}

</style>
