<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nh-vabciq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-broken-20-filled" /></template>
<style>
.nh-vabciq {
  fill: currentColor;
  d: path("M7.225 10.082a.5.5 0 0 1 .629.064l2.646 2.647l1.646-1.646l.079-.065a.5.5 0 0 1 .629.064l3 3A.5.5 0 0 1 16 14.5v.5a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-1.5a.5.5 0 0 1 .146-.354l3-3zM13 2a3 3 0 0 1 3 3v5.5a.5.5 0 0 1-.854.354L12.5 8.207l-1.646 1.647a.5.5 0 0 1-.707 0L7.5 7.207L4.854 9.854A.5.5 0 0 1 4 9.5V5a3 3 0 0 1 3-3z");
}

</style>
