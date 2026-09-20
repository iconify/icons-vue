<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="ibazdcbva"/><path class="hhc1xw5st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:exclamation-mark" /></template>
<style>
.hhc1xw5st {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M21 24a3 3 0 0 1-6 0V5a3 3 0 1 1 6 0z");
}

.ibazdcbva {
  cx: 18px;
  cy: 32px;
  r: 3px;
  fill: var(--svg-color--be1931, #be1931);
}

</style>
