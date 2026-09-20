<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqwjjtbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dock-to-left-outline-sharp" /></template>
<style>
.fqwjjtbma {
  fill: currentColor;
  d: path("M16 19h3V5h-3zM5 19h9V5H5zm11 0h3zM3 21V3h18v18z");
}

</style>
