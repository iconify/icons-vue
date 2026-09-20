<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi3dvnf7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:horizontal-rule-outline" /></template>
<style>
.hi3dvnf7f {
  fill: currentColor;
  d: path("M4 13v-2h16v2z");
}

</style>
