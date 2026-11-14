<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws-oeibkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:checkbox" /></template>
<style>
.ws-oeibkb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.375 3.25h7.25q2.123 0 3.624 1.501t1.501 3.624v7.25q0 2.123-1.501 3.624t-3.624 1.501h-7.25q-2.123 0-3.624-1.501T3.25 15.625v-7.25q0-2.123 1.501-3.624T8.375 3.25");
}

</style>
