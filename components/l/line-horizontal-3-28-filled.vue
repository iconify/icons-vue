<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="f1i96f3ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-3-28-filled" /></template>
<style>
.f1i96f3ay {
  fill: currentColor;
  d: path("M2.003 6a1 1 0 0 1 1-1h22a1 1 0 1 1 0 2h-22a1 1 0 0 1-1-1M2 22a1 1 0 0 1 1-1h22a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m1-9a1 1 0 1 0 0 2h22a1 1 0 1 0 0-2z");
}

</style>
