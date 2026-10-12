<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8hmnpbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-grip-sharp" /></template>
<style>
.d8hmnpbqo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25a2.75 2.75 0 1 0 0 5.5a2.75 2.75 0 1 0 0-5.5m-1.75 5L8.9 11.9m4.85-3.65l1.35 3.65m-8.8 1.75l-1.55 4.47l-.52 1.52l1.51.52l.52.18l1.51.52l.53-1.51l1.55-4.47l.52-1.52l-1.51-.52l-.52-.18l-1.51-.52zm7.85 1.23l1.55 4.47l.53 1.51l1.51-.52l.52-.18l1.51-.52l-.52-1.52l-1.55-4.47l-.53-1.51l-1.51.52l-.52.18l-1.51.52z");
}

</style>
