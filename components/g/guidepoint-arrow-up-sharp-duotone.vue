<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zhk6iiz1t"/><path class="nxiwqo1kf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:guidepoint-arrow-up-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nxiwqo1kf {
  d: path("M15.999 16V18H7.999V16H15.999ZM12.005 3C12.275 3.03 12.635 3.19 12.8 3.41L17.285 9.41C17.483 9.67 17.514 10.08 17.411 10.39C17.241 10.73 16.863 11 16.485 11H7.512C7.134 11 6.787 10.79 6.617 10.45C6.448 10.11 6.485 9.71 6.711 9.41L11.228 3.36C11.392 3.19 11.768 3.02 12.005 3Z");
}

.zhk6iiz1t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 13C7.209 13 9 14.79 9 17C9 19.21 7.209 21 5 21C2.791 21 1 19.21 1 17C1 14.79 2.791 13 5 13ZM19 13C21.209 13 23 14.79 23 17C23 19.21 21.209 21 19 21C16.791 21 15 19.21 15 17C15 14.79 16.791 13 19 13Z");
}

</style>
