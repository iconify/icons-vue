<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4sdvcb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-auto-awesome-motion" /></template>
<style>
.r4sdvcb7d {
  fill: currentColor;
  d: path("M14 2H4a2 2 0 0 0-2 2v10h2V4h10zm4 4H8a2 2 0 0 0-2 2v10h2V8h10zm2 4h-8a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h8c1.1 0 2-.9 2-2v-8c0-1.1-.9-2-2-2");
}

</style>
