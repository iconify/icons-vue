<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5-zjsayx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:approval-outline-sharp" /></template>
<style>
.s5-zjsayx {
  fill: currentColor;
  d: path("M4 22v-8h16v8zm2-4h12v-2H6zm6-4L7 7q0-2.075 1.463-3.537T12 2t3.538 1.463T17 7zm0-2.8L15 7q0-1.25-.875-2.125T12 4t-2.125.875T9 7zm0-3.6");
}

</style>
