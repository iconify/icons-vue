<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xugo0db9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:apps-plus" /></template>
<style>
.xugo0db9o {
  fill: currentColor;
  d: path("M11 20h11v-7H11zm-9-9h10V4H2zm0 9h7v-7H2zm15-9V8h-3V6h3V3h2v3h3v2h-3v3z");
}

</style>
