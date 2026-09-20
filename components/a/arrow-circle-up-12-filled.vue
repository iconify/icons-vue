<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qa1y_4bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-up-12-filled" /></template>
<style>
.qa1y_4bsn {
  fill: currentColor;
  d: path("M1 6a5 5 0 1 1 10 0A5 5 0 0 1 1 6m2.646-.098a.5.5 0 0 0 .708 0L5.5 4.756V8.5a.5.5 0 0 0 1 0V4.756l1.146 1.146a.5.5 0 1 0 .708-.707l-2-2a.5.5 0 0 0-.708 0l-2 2a.5.5 0 0 0 0 .707");
}

</style>
