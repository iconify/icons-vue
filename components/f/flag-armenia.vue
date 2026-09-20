<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bd2qqlspu"/><path class="qlfpp-jbs"/><path class="evf69ej7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-armenia" /></template>
<style>
.bd2qqlspu {
  fill: var(--svg-color--d90012, #d90012);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4");
}

.evf69ej7v {
  fill: var(--svg-color--0033a0, #0033a0);
  d: path("M0 13h36v10H0z");
}

.qlfpp-jbs {
  fill: var(--svg-color--f2a800, #f2a800);
  d: path("M4 31h28a4 4 0 0 0 4-4v-4H0v4a4 4 0 0 0 4 4");
}

</style>
