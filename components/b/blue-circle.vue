<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="zftiqseks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:blue-circle" /></template>
<style>
.zftiqseks {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--0071bc, #0071bc);
}

</style>
