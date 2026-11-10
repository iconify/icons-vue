<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fifvrfb3s"/><path class="p3yt7gfqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-end-vertical-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fifvrfb3s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 13C17.6569 13 19 14.343 19 16V18C19 19.657 17.6569 21 16 21H4C2.3432 21 1 19.657 1 18V16C1 14.343 2.3432 13 4 13H16ZM16 3C17.6569 3 19 4.343 19 6V8C19 9.657 17.6569 11 16 11H12C10.3431 11 9 9.657 9 8V6C9 4.343 10.3431 3 12 3H16Z");
}

.p3yt7gfqy {
  d: path("M22 1C22.5523 1 23 1.448 23 2V22C23 22.552 22.5523 23 22 23C21.4477 23 21 22.552 21 22V2C21 1.448 21.4477 1 22 1Z");
}

</style>
