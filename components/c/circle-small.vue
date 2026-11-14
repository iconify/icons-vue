<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpaf7jbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:circle-small" /></template>
<style>
.xpaf7jbho {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 12q0-1.968 1.391-3.359T12 7.25t3.359 1.391T16.75 12t-1.391 3.359T12 16.75t-3.359-1.391T7.25 12");
}

</style>
