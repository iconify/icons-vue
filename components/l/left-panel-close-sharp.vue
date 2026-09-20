<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8g0jsbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:left-panel-close-sharp" /></template>
<style>
.x8g0jsbgp {
  fill: currentColor;
  d: path("M15.596 15.173V8.827L12.404 12zM9 19h10V5H9zm-5 1V4h16v16z");
}

</style>
