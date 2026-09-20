<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="af2obl-3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-1-dashes-16-regular" /></template>
<style>
.af2obl-3u {
  fill: currentColor;
  d: path("M2 7.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1-.5-.5m4.5 0A.5.5 0 0 1 7 7h2a.5.5 0 0 1 0 1H7a.5.5 0 0 1-.5-.5m4.5 0a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1-.5-.5");
}

</style>
