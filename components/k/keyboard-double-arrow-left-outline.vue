<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_ge4sbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-double-arrow-left-outline" /></template>
<style>
.f_ge4sbfb {
  fill: currentColor;
  d: path("m11 18l-6-6l6-6l1.4 1.4L7.825 12l4.575 4.6zm6.6 0l-6-6l6-6L19 7.4L14.425 12L19 16.6z");
}

</style>
