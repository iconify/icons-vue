<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="rkf-s6b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-2-dashes-solid-28-filled" /></template>
<style>
.rkf-s6b5a {
  fill: currentColor;
  d: path("M3 9a1 1 0 0 0 0 2h4a1 1 0 1 0 0-2zm9 0a1 1 0 1 0 0 2h4a1 1 0 1 0 0-2zm9 0a1 1 0 1 0 0 2h4a1 1 0 1 0 0-2zM3 17a1 1 0 1 0 0 2h22a1 1 0 1 0 0-2z");
}

</style>
