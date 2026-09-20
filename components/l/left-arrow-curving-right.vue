<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="f0coyab8t"/><path class="ymyxxybgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:left-arrow-curving-right" /></template>
<style>
.f0coyab8t {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M0 32a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V4a4 4 0 0 0-4-4H4a4 4 0 0 0-4 4z");
}

.ymyxxybgh {
  fill: var(--svg-color--fff, #fff);
  d: path("M29.2 25L22 19v4h-4a7 7 0 0 1 0-14h8V5h-8C11.926 5 7 9.925 7 16c0 6.074 4.926 11 11 11h4v4z");
}

</style>
