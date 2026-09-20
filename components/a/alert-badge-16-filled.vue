<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="madhwnb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:alert-badge-16-filled" /></template>
<style>
.madhwnb0y {
  fill: currentColor;
  d: path("M8 2a4.5 4.5 0 0 0-4.5 4.5v2.401l-.964 2.414A.5.5 0 0 0 3 12h10a.5.5 0 0 0 .464-.685L12.5 8.9V7a2.5 2.5 0 0 1-1.874-4.155A4.48 4.48 0 0 0 8 2m0 12.5A2 2 0 0 1 6.063 13h3.874A2 2 0 0 1 8 14.5M12.5 6a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

</style>
