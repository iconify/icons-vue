<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6o18dbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-l" /></template>
<style>
.y6o18dbap {
  fill: currentColor;
  d: path("M3 19V8.27q0-1.357.977-2.323t2.35-.966h11.346q1.373 0 2.35.966T21 8.269V19zm7.864-3.879h3.773v-.838h-2.918v-5.38h-.855z");
}

</style>
