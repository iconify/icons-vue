<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1844i72d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:align-center-both" /></template>
<style>
.k1844i72d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.625 5.25h2.625v6h-6V8.625q0-3.375 3.375-3.375m-3.375 7.5v2.625q0 3.375 3.375 3.375h2.625v-6zm7.5 0v6h2.625q3.375 0 3.375-3.375V12.75zm6-1.5V8.625q0-3.375-3.375-3.375H12.75v6z");
}

</style>
