<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r9yej-wks"/><path class="ht07jacwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-space-around-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ht07jacwd {
  d: path("M4 1C4.5523 1 5 1.448 5 2V22C5 22.552 4.5523 23 4 23C3.4477 23 3 22.552 3 22V2C3 1.448 3.4477 1 4 1ZM20 1C20.5523 1 21 1.448 21 2V22C21 22.552 20.5523 23 20 23C19.4477 23 19 22.552 19 22V2C19 1.448 19.4477 1 20 1Z");
}

.r9yej-wks {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 6C14.6569 6 16 7.344 16 9V15C16 16.655 14.6671 18 13 18H11C9.3555 18 8 16.667 8 15V9C8 7.351 9.3412 6 11 6H13Z");
}

</style>
