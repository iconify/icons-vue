<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdsh54kxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hangout-video-outline-sharp" /></template>
<style>
.pdsh54kxh {
  fill: currentColor;
  d: path("M6 16h8v-3.2l4 3.2V8l-4 3.2V8H6zm-4 4V4h20v16zm2-2h16V6H4zM4 6v12z");
}

</style>
