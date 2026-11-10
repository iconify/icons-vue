<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tvh4vkn6w"/><path class="j9uwlvxoa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-end-vertical-sharp-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j9uwlvxoa {
  d: path("M18 3C18.552 3 19 3.448 19 4V10C19 10.552 18.552 11 18 11H10C9.448 11 9 10.552 9 10V4C9 3.448 9.448 3 10 3H18Z");
}

.tvh4vkn6w {
  d: path("M23 1V23H21V1H23ZM18 13C18.552 13 19 13.448 19 14V20C19 20.552 18.552 21 18 21H2C1.448 21 1 20.552 1 20V14C1 13.448 1.448 13 2 13H18Z");
}

</style>
