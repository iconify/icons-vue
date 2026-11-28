<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="otxk-mb9o"/><path clip-rule="evenodd" class="txf6e8b4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-space-between-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.otxk-mb9o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 6H7C8.6569 6 10 7.3431 10 9V15C10 16.6569 8.6569 18 7 18H6C4.3431 18 3 16.6569 3 15V9C3 7.3431 4.3431 6 6 6ZM18 6H17C15.3431 6 14 7.3431 14 9V15C14 16.6569 15.3431 18 17 18H18C19.6569 18 21 16.6569 21 15V9C21 7.3431 19.6569 6 18 6Z");
}

.txf6e8b4f {
  fill-rule: evenodd;
  d: path("M4 1C4.5523 1 5 1.4477 5 2V22C5 22.5523 4.5523 23 4 23C3.4477 23 3 22.5523 3 22V2C3 1.4477 3.4477 1 4 1ZM20 1C20.5523 1 21 1.4477 21 2V22C21 22.5523 20.5523 23 20 23C19.4477 23 19 22.5523 19 22V2C19 1.4477 19.4477 1 20 1Z");
}

</style>
