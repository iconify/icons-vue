<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk9yzt_fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-neutral-fill-round" /></template>
<style>
.zk9yzt_fc {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m7.01-4H9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m6 0H15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m.99 6H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2");
}

</style>
