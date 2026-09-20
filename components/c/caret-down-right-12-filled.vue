<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fvcvx1bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-down-right-12-filled" /></template>
<style>
.fvcvx1bjo {
  fill: currentColor;
  d: path("M9.005 3.963c0-.891-1.077-1.337-1.707-.707L3.255 7.299c-.63.63-.184 1.707.707 1.707h3.543a1.5 1.5 0 0 0 1.5-1.5z");
}

</style>
