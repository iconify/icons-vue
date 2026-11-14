<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb3thubvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drum-key" /></template>
<style>
.vb3thubvh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 2.25h13.5q1.243 0 2.121.879q.879.878.879 2.121q0 3-3 3h-6v6h.563q2.937.001 2.937 2.938v2.125q-.001 2.936-2.937 2.937h-2.625q-2.937 0-2.938-2.937v-2.125q0-2.938 2.938-2.938h.562v-6h-6q-1.243 0-2.121-.879q-.879-.878-.879-2.121t.879-2.121q.878-.879 2.121-.879");
}

</style>
