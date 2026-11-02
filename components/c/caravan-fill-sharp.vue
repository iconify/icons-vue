<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f54jenbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caravan-fill-sharp" /></template>
<style>
.f54jenbmy {
  fill: currentColor;
  d: path("M2 18V5a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v9h3a1 1 0 0 1 0 2h-3v2a1 1 0 0 1-1 1h-4.171a3 3 0 0 1-5.658 0H3a1 1 0 0 1-1-1M6 8v6h8V8Zm3.293 10.707l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0-.002-1.412l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 .002 1.412");
}

</style>
