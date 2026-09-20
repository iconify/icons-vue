<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9ocmub5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-double-arrow-right" /></template>
<style>
.k9ocmub5o {
  fill: currentColor;
  d: path("M9.575 12L5 7.4L6.4 6l6 6l-6 6L5 16.6zm6.6 0L11.6 7.4L13 6l6 6l-6 6l-1.4-1.4z");
}

</style>
