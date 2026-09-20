<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbssdmbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-bar-outline-rounded" /></template>
<style>
.vbssdmbce {
  fill: currentColor;
  d: path("M11.5 19.5v-6.462l-6.666-7.5q-.114-.123-.186-.284q-.071-.162-.071-.331q0-.4.271-.662T5.512 4h12.977q.392 0 .663.26t.271.655q0 .168-.071.333t-.186.29l-6.666 7.5V19.5h4q.213 0 .356.144t.144.357t-.144.356t-.356.143h-9q-.213 0-.356-.144T7 19.999t.144-.356t.356-.143zM7.45 7h9.1l1.8-2H5.65zM12 12.1L15.66 8H8.34zm0 0");
}

</style>
