<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="lzpq-ccsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:black-circle" /></template>
<style>
.lzpq-ccsc {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: currentColor;
}

</style>
