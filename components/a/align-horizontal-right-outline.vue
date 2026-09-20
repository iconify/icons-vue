<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d028cbbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-horizontal-right-outline" /></template>
<style>
.d028cbbvj {
  fill: currentColor;
  d: path("M19.23 21V3h1v18zm-9.46-4.692v-2.039h6.884v2.039zm-6-6.577V7.692h12.884v2.039z");
}

</style>
