<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="msawfrb7w"/><path class="fvfcp566l"/><path class="e56ncibgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-nauru" /></template>
<style>
.e56ncibgf {
  fill: var(--svg-color--fff, #fff);
  d: path("m16 41.2l1.2-2.2l.3 2.5l1.9-1.6l-.7 2.4l2.4-.7l-1.6 1.9l2.5.3l-2.2 1.2l2.2 1.2l-2.5.3l1.6 1.9l-2.4-.7l.7 2.4l-1.9-1.6l-.3 2.5l-1.2-2.2l-1.2 2.2l-.3-2.5l-1.9 1.6l.7-2.4l-2.4.7l1.6-1.9l-2.5-.3l2.2-1.2l-2.2-1.2l2.5-.3l-1.6-1.9l2.4.7l-.7-2.4l1.9 1.6l.3-2.5z");
}

.fvfcp566l {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M61.7 28H2.3c-.2 1.3-.3 2.6-.3 4s.1 2.7.3 4h59.5c.2-1.3.3-2.6.3-4s-.2-2.7-.4-4");
}

.msawfrb7w {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M32 2C16.8 2 4.2 13.3 2.3 28h59.5C59.8 13.3 47.2 2 32 2m0 60c15.2 0 27.8-11.3 29.7-26H2.3C4.2 50.7 16.8 62 32 62");
}

</style>
