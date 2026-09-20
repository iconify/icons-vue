<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj0s6zbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-end" /></template>
<style>
.lj0s6zbtx {
  fill: currentColor;
  d: path("M2 22v-2h20v2zm5-11V8h10v3zm0 6v-3h10v3z");
}

</style>
