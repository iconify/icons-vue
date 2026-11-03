<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr3609b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmarks" /></template>
<style>
.lr3609b1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9C4 7.8954 4.8954 7 6 7L14 7C15.1046 7 16 7.8954 16 9L16 21.2488C16 21.8422 15.3436 22.2005 14.8444 21.8797L10.6083 19.6386C10.2378 19.4004 9.76225 19.4004 9.39167 19.6386L5.1556 21.8797C4.6564 22.2005 4 21.8422 4 21.2488ZM20 17.1987L20 4C20 2.8954 19.1046 2 18 2L10 2C9.2855 2 8.6253 2.3812 8.2679 3");
}

</style>
