<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><rect class="mwyb9cv3b"/><rect class="w-0i0z5mu"/><rect class="mwyb9cv3b"/><rect class="w-0i0z5mu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:cloud-filled" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mwyb9cv3b {
  width: 16px;
  height: 8px;
  x: 2px;
  y: 6px;
  rx: 4px;
}

.w-0i0z5mu {
  width: 9px;
  height: 8px;
  x: 6px;
  y: 3px;
  rx: 4px;
}

</style>
