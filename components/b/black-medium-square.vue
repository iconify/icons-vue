<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="evy9s1f1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:black-medium-square" /></template>
<style>
.evy9s1f1x {
  fill: var(--svg-color--354a54, #354a54);
  d: path("M53.799 49.21a4.7 4.7 0 0 1-4.701 4.702h-34.2A4.7 4.7 0 0 1 10.2 49.21v-34.2a4.7 4.7 0 0 1 4.698-4.701h34.2a4.7 4.7 0 0 1 4.701 4.701z");
}

</style>
