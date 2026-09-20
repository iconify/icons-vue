<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcc63cbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-read-play-sharp" /></template>
<style>
.rcc63cbuv {
  fill: currentColor;
  d: path("m10 14l6-4l-6-4zm-8 8V2h20v16H6z");
}

</style>
