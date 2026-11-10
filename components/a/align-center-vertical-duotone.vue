<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h5xsjbc4m"/><path class="xa745zbpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-center-vertical-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h5xsjbc4m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 13C19.6569 13 21 14.343 21 16V18C21 19.657 19.6569 21 18 21H6C4.3432 21 3 19.657 3 18V16C3 14.343 4.3432 13 6 13H18ZM14 3C15.6569 3 17 4.343 17 6V8C17 9.657 15.6569 11 14 11H10C8.3431 11 7 9.657 7 8V6C7 4.343 8.3431 3 10 3H14Z");
}

.xa745zbpp {
  d: path("M12 19C12.5523 19 13 19.448 13 20V22C13 22.552 12.5523 23 12 23C11.4477 23 11 22.552 11 22V20C11 19.448 11.4477 19 12 19ZM12 9C12.5523 9 13 9.448 13 10V14C13 14.552 12.5523 15 12 15C11.4477 15 11 14.552 11 14V10C11 9.448 11.4477 9 12 9ZM12 1C12.5523 1 13 1.448 13 2V4C13 4.552 12.5523 5 12 5C11.4477 5 11 4.552 11 4V2C11 1.448 11.4477 1 12 1Z");
}

</style>
