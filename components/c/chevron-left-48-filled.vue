<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sjz4eilgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-left-48-filled" /></template>
<style>
.sjz4eilgc {
  fill: currentColor;
  d: path("M32.06 8.19a1.5 1.5 0 0 1 0 2.12L18.622 23.75l13.44 13.44a1.5 1.5 0 0 1-2.122 2.12l-14.5-14.5a1.5 1.5 0 0 1 0-2.12l14.5-14.5a1.5 1.5 0 0 1 2.122 0");
}

</style>
