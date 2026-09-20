<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xo-ygvgzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hexagon-20-regular" /></template>
<style>
.xo-ygvgzz {
  fill: currentColor;
  d: path("M6.826 4a.5.5 0 0 0-.433.25l-3.176 5.5a.5.5 0 0 0 0 .5l3.176 5.5a.5.5 0 0 0 .433.25h6.35a.5.5 0 0 0 .433-.25l3.176-5.5a.5.5 0 0 0 0-.5l-3.176-5.5a.5.5 0 0 0-.433-.25zm-1.3-.25a1.5 1.5 0 0 1 1.3-.75h6.35a1.5 1.5 0 0 1 1.3.75l3.175 5.5a1.5 1.5 0 0 1 0 1.5l-3.176 5.5a1.5 1.5 0 0 1-1.299.75h-6.35a1.5 1.5 0 0 1-1.3-.75l-3.175-5.5a1.5 1.5 0 0 1 0-1.5z");
}

</style>
