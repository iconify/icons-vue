<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="phm49tbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:black-circle" /></template>
<style>
.phm49tbyx {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--3e4347, #3e4347);
}

</style>
