<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ilxykjbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:card-chip-fill" /></template>
<style>
.ilxykjbwp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 3L19 3C21.2092 3 23 4.7908 23 7L23 17C23 19.2092 21.2092 21 19 21L5 21C2.7908 21 1 19.2092 1 17L1 7C1 4.7908 2.7908 3 5 3ZM16 16L21 16L21 14L16 14L16 10L21 10L21 8L16 8L16 5L14 5L14 19L16 19L16 16ZM8 14L3 14L3 16L8 16L8 19L10 19L10 5L8 5L8 8L3 8L3 10L8 10L8 14Z");
}

</style>
