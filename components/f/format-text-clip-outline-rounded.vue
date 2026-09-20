<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qptnepbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-text-clip-outline-rounded" /></template>
<style>
.qptnepbru {
  fill: currentColor;
  d: path("M5.22 19.356q-.143-.143-.143-.356V5q0-.213.144-.356q.144-.144.357-.144t.356.144t.143.356v14q0 .213-.144.356t-.357.144t-.356-.144m12.846 0q-.143-.144-.143-.356v-6.5H9.346q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h8.577V5q0-.213.144-.356t.357-.144t.356.144t.143.356v14q0 .213-.144.356q-.144.144-.356.144q-.213 0-.357-.144");
}

</style>
