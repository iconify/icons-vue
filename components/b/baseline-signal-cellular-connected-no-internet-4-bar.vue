<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpw9dxmnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-signal-cellular-connected-no-internet-4-bar" /></template>
<style>
.mpw9dxmnm {
  fill: currentColor;
  d: path("M20 18h2v-8h-2zm0 4h2v-2h-2zM2 22h16V8h4V2z");
}

</style>
