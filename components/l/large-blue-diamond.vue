<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="b8act2bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:large-blue-diamond" /></template>
<style>
.b8act2bim {
  fill: var(--svg-color--0071b8, #0071b8);
  d: path("M2.018 32L32 2.019l29.981 29.98L32 61.982z");
}

</style>
