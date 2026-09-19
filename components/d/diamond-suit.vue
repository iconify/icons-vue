<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g7_vbg8je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:diamond-suit" /></template>
<style>
.g7_vbg8je {
  fill: var(--svg-color--e03a4d, #e03a4d);
  d: path("M56.28 32L32.14 63L8 32L32.14 1");
}

</style>
