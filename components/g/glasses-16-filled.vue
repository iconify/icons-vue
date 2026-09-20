<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hsz4uc8rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:glasses-16-filled" /></template>
<style>
.hsz4uc8rv {
  fill: currentColor;
  d: path("M5.168 3.126A.5.5 0 0 1 5.5 3h1a.5.5 0 0 1 0 1h-.81L3.438 6H5.5A1.5 1.5 0 0 1 7 7.5V8h2v-.5A1.5 1.5 0 0 1 10.5 6h2.062L10.31 4H9.5a.5.5 0 0 1 0-1h1a.5.5 0 0 1 .332.126l3.622 3.216A1.5 1.5 0 0 1 15 7.5v2a2.5 2.5 0 0 1-2.5 2.5h-1A2.5 2.5 0 0 1 9 9.5V9H7v.5A2.5 2.5 0 0 1 4.5 12h-1A2.5 2.5 0 0 1 1 9.5v-2a1.5 1.5 0 0 1 .546-1.158z");
}

</style>
