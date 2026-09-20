<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1f216bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:key-vertical" /></template>
<style>
.h1f216bul {
  fill: currentColor;
  d: path("M14.125 9.125Q15 8.25 15 7t-.875-2.125T12 4t-2.125.875T9 7t.875 2.125T12 10t2.125-.875M12.05 23L8 19l2-2l-2-2l2-2v-.35q-1.8-.625-2.9-2.175T6 7q0-2.5 1.75-4.25T12 1t4.25 1.75T18 7q0 2.025-1.15 3.538T14 12.65V21z");
}

</style>
