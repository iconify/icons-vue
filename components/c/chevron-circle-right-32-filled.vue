<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t-hbj0bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-right-32-filled" /></template>
<style>
.t-hbj0bls {
  fill: currentColor;
  d: path("M2 16C2 8.268 8.268 2 16 2s14 6.268 14 14s-6.268 14-14 14S2 23.732 2 16m12.707-6.707a1 1 0 1 0-1.414 1.414L18.586 16l-5.293 5.293a1 1 0 0 0 1.414 1.414l5.879-5.878l.028-.033q.035-.04.073-.08A1 1 0 0 0 20.98 16c.003-.26-.097-.484-.293-.718a1 1 0 0 0-.1-.11h-.002z");
}

</style>
