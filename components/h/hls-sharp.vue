<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyfpnxbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hls-sharp" /></template>
<style>
.cyfpnxbnz {
  fill: currentColor;
  d: path("M3 15V9h1.5v2h2V9H8v6H6.5v-2.5h-2V15zm7 0V9h1.5v4.5H14V15zm5.5 0v-2H17v.5h2v-1h-3.5V9h5v2H19v-.5h-2v1h3.5V15z");
}

</style>
