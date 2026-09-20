<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvxnsgsnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:help-clinic" /></template>
<style>
.hvxnsgsnn {
  fill: currentColor;
  d: path("M11.5 16.692h1v-4h-1zm1.04-6.383q.23-.23.23-.54t-.23-.54Q12.31 9 12 9t-.54.23t-.23.54t.23.539t.54.23t.54-.23M5 20V9.5l7-5.27l7 5.27V20z");
}

</style>
