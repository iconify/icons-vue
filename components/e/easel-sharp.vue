<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7bg-j5tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:easel-sharp" /></template>
<style>
.w7bg-j5tn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3L20 3L20 16L4 16L4 3ZM1 16L23 16M8 16L6.2862 21.7127M16 16L17.7138 21.7127M12 16L12 20");
}

</style>
