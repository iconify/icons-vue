<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="zbmadxg-s"/><path class="ck6wk875b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-up-down-duotone" /></template>
<style>
.ck6wk875b {
  d: path("M176 168H80a8 8 0 0 0-5.66 13.66l48 48a8 8 0 0 0 11.32 0l48-48A8 8 0 0 0 176 168m-48 44.69L99.31 184h57.38ZM80 88h96a8 8 0 0 0 5.66-13.66l-48-48a8 8 0 0 0-11.32 0l-48 48A8 8 0 0 0 80 88m48-44.69L156.69 72H99.31Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.zbmadxg-s {
  d: path("M80 176h96l-48 48Zm48-144L80 80h96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
