<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7e3qb7bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-copy-off" /></template>
<style>
.y7e3qb7bw {
  fill: currentColor;
  d: path("m21 18.15l-15-15V3q0-.825.588-1.412T8 1h7l6 6zm-.5 5.15L16.2 19H8q-.825 0-1.412-.587T6 17V8.8L.7 3.5l1.4-1.4l19.8 19.8zM14 8h5.5L14 2.5L19.5 8L14 2.5zM4 23q-.825 0-1.412-.587T2 21V8h2v13h12v2z");
}

</style>
