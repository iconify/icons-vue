<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="f0coyab8t"/><path class="eemovib3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:fast-reverse-button" /></template>
<style>
.eemovib3r {
  fill: var(--svg-color--fff, #fff);
  d: path("M6 18L18 7v9.166L28 7v22l-10-9.167V29z");
}

.f0coyab8t {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M0 32a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V4a4 4 0 0 0-4-4H4a4 4 0 0 0-4 4z");
}

</style>
