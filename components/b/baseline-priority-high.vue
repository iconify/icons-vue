<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="rpxe9ibnu"/><path class="xi7mcbcba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-priority-high" /></template>
<style>
.rpxe9ibnu {
  cx: 12px;
  cy: 19px;
  r: 2px;
  fill: currentColor;
}

.xi7mcbcba {
  fill: currentColor;
  d: path("M10 3h4v12h-4z");
}

</style>
