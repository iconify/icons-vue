<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="opaepuy9b"/><path class="jg6y2wg_d"/><path class="g91g_4_aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-madagascar" /></template>
<style>
.g91g_4_aj {
  fill: var(--svg-color--eee, #eee);
  d: path("M13 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h9z");
}

.jg6y2wg_d {
  fill: var(--svg-color--007e3a, #007e3a);
  d: path("M13 31h19a4 4 0 0 0 4-4v-9H13z");
}

.opaepuy9b {
  fill: var(--svg-color--fc3d32, #fc3d32);
  d: path("M32 5H13v13h23V9a4 4 0 0 0-4-4");
}

</style>
