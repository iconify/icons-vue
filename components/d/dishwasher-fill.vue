<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rduel1bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dishwasher-fill" /></template>
<style>
.rduel1bnq {
  fill: currentColor;
  d: path("M6 2h12a3 3 0 0 1 3 3v3H3V5a3 3 0 0 1 3-3m2.01 3H8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M11 5a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm10 5v9a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-9Zm-5 2H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2");
}

</style>
