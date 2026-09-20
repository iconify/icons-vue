<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inktik0hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bubbles-outline-sharp" /></template>
<style>
.inktik0hu {
  fill: currentColor;
  d: path("M10.05 7.65L13 10.575V8.35h2V14H9.35v-2h2.25L8.65 9.05zM19 20q-1.25 0-2.125-.875T16 17t.875-2.125T19 14t2.125.875T22 17t-.875 2.125T19 20M2 20V4h20v8h-2V6H4v12h10v2z");
}

</style>
