<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbqt2e85i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-big-down" /></template>
<style>
.qbqt2e85i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.614 19.174l-4.553-4.553q-.795-.794-.365-1.833T6.25 11.75q.621 0 1.061-.439q.439-.44.439-1.061V6.125q0-3.375 3.375-3.375h1.75q3.375 0 3.375 3.375v4.125q0 .621.439 1.061q.44.439 1.061.439q1.124 0 1.554 1.038t-.365 1.833l-4.553 4.553q-2.386 2.386-4.772 0");
}

</style>
