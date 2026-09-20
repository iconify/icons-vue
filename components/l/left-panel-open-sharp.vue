<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxluin9bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:left-panel-open-sharp" /></template>
<style>
.lxluin9bm {
  fill: currentColor;
  d: path("M12.404 8.827v6.346L15.596 12zM9 19h10V5H9zm-5 1V4h16v16z");
}

</style>
