<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwsu1dx3v"/><path class="bma86-brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-pause-presentation" /></template>
<style>
.bma86-brq {
  fill: currentColor;
  d: path("M9 8h2v8H9zm4 0h2v8h-2z");
}

.pwsu1dx3v {
  fill: currentColor;
  d: path("M21 19.1H3V5h18zM21 3H3c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2");
}

</style>
