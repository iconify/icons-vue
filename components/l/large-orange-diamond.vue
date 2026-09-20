<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e51qerblb"/><path class="i1-edabxp"/><path class="v1wvdmxdy"/><circle class="v1fzqtj6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:large-orange-diamond" /></template>
<style>
.e51qerblb {
  fill: var(--svg-color--f77e00, #f77e00);
  d: path("m70.04 6.32l52.2 52a7.887 7.887 0 0 1-.2 11.1l-52 52.2a7.99 7.99 0 0 1-11.3 0l-52-52.2a8 8 0 0 1-.2-11.1l52.2-52a7.99 7.99 0 0 1 11.3 0");
}

.i1-edabxp {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("m65.14 10.42l48.5 48.4a7.27 7.27 0 0 1-.18 10.28l-.02.02l-48.4 48.5a7.42 7.42 0 0 1-10.49.01l-.01-.01l-48.3-48.5a7.28 7.28 0 0 1-.21-10.29l.01-.01l48.6-48.4c2.9-2.9 7.59-2.9 10.5 0");
}

.v1fzqtj6p {
  cx: 15.94px;
  cy: 60.43px;
  r: 3.3px;
  fill: var(--svg-color--ffbd52, #ffbd52);
}

.v1wvdmxdy {
  fill: var(--svg-color--ffbd52, #ffbd52);
  d: path("M53.34 17.62c-1.6 1.1-33.1 32.3-33.1 32.3s-2.6 2.3-.8 4.7c1.7 2.2 4.3 1.1 5.6-.1s29.7-29 30.9-30.4a5.43 5.43 0 0 0 .6-5.5c-.8-1.6-2.1-1.8-3.2-1");
}

</style>
