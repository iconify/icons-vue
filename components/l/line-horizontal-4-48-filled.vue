<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xzyapnbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-48-filled" /></template>
<style>
.xzyapnbjx {
  fill: currentColor;
  d: path("M42.5 38a1.5 1.5 0 0 1 0 3h-37a1.5 1.5 0 0 1 0-3zm0-10a1.5 1.5 0 0 1 0 3h-37a1.5 1.5 0 0 1 0-3zm0-10a1.5 1.5 0 0 1 0 3h-37a1.5 1.5 0 0 1 0-3zm0-10a1.5 1.5 0 0 1 0 3h-37a1.5 1.5 0 0 1 0-3z");
}

</style>
