<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npn_y_bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-circle-rounded" /></template>
<style>
.npn_y_bgr {
  fill: currentColor;
  d: path("M16 18q-2.25 0-3.912-1.425T10.075 13H3q-.425 0-.712-.288T2 12t.288-.712T3 11h7.075q.35-2.15 2.013-3.575T16 6q2.5 0 4.25 1.75T22 12t-1.75 4.25T16 18");
}

</style>
