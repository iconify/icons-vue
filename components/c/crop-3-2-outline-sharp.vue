<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klxs3jbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-3-2-outline-sharp" /></template>
<style>
.klxs3jbia {
  fill: currentColor;
  d: path("M4 17V7h16v10zm1-1h14V8H5zm0 0V8z");
}

</style>
