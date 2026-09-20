<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="a5xi96bne"/><path class="k_n3z371w"/><circle class="epnranbcj"/><path class="tm_vyrbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:double-exclamation-mark" /></template>
<style>
.a5xi96bne {
  cx: 11px;
  cy: 31px;
  r: 3px;
  fill: var(--svg-color--be1931, #be1931);
}

.epnranbcj {
  cx: 25px;
  cy: 31px;
  r: 3px;
  fill: var(--svg-color--be1931, #be1931);
}

.k_n3z371w {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M14 23a3 3 0 1 1-6 0V4a3 3 0 1 1 6 0z");
}

.tm_vyrbaw {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M28 23a3 3 0 0 1-6 0V4a3 3 0 0 1 6 0z");
}

</style>
