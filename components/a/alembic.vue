<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jfqw_jb_y"/><path class="oh-stzbhp"/><path class="uih337buo"/><path class="bc74s0b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:alembic" /></template>
<style>
.bc74s0b1c {
  fill: var(--svg-color--c5ccd6, #c5ccd6);
  d: path("M9.2 36.5c0 1 .8 1.8 1.8 1.8h39.5c1 0 1.8-.8 1.8-1.8s-.8-1.8-1.8-1.8H11c-1-.1-1.8.8-1.8 1.8");
}

.jfqw_jb_y {
  fill: var(--svg-color--a1d8f2, #a1d8f2);
  d: path("m60.5 26.9l1.5-2.7S42.2 12.1 35.2 10.5c-1.5-.4-3-.6-4.6-.6c-10.4 0-18.8 8.6-18.8 19.2s8.4 19.2 18.8 19.2s18.8-8.6 18.8-19.2c0-2.1-.3-4.1-1-6z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.oh-stzbhp {
  fill: var(--svg-color--bd80ff, #bd80ff);
  d: path("M14.6 29c0 9.1 7.2 16.6 16.2 16.6S46.9 38.1 46.9 29z");
}

.uih337buo {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M15.5 34.6h-3.6L2 62h1.8zm30.5 0h3.6L59.4 62h-1.8zM31.6 62h-1.8l-.9-27.4h3.6z");
}

</style>
