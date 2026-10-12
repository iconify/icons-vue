<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="jb33z1bix"/><path class="ly86fufep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-todo-circle-fill" /></template>
<style>
.jb33z1bix {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 7C9 9.2091 7.2091 11 5 11C2.7909 11 1 9.2091 1 7C1 4.7909 2.7909 3 5 3C7.2091 3 9 4.7909 9 7ZM9 17C9 19.2091 7.2091 21 5 21C2.7909 21 1 19.2091 1 17C1 14.7909 2.7909 13 5 13C7.2091 13 9 14.7909 9 17Z");
  stroke: none;
}

.ly86fufep {
  d: path("M12 7L22 7M12 17L22 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
