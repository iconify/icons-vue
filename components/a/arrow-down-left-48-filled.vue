<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t19_nxbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-left-48-filled" /></template>
<style>
.t19_nxbav {
  fill: currentColor;
  d: path("M25.5 42a1.5 1.5 0 0 0 0-3H11.121l30.44-30.44a1.5 1.5 0 0 0-2.122-2.12L9 36.878V22.5a1.5 1.5 0 0 0-3 0v18A1.5 1.5 0 0 0 7.5 42z");
}

</style>
