<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd-i-ywcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:magnify-fullscreen-outline-sharp" /></template>
<style>
.yd-i-ywcu {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm0 0V6zm10-4h2v-2h2v-2h-2V8h-2v2h-2v2h2z");
}

</style>
