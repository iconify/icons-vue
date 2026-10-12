<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="he0k8t_zu"/><path class="xdcgmbvng"/><path class="lvbr6r3id"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-todo-circle-two-tone" /></template>
<style>
.he0k8t_zu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M9 7C9 9.2091 7.2091 11 5 11C2.7909 11 1 9.2091 1 7C1 4.7909 2.7909 3 5 3C7.2091 3 9 4.7909 9 7ZM9 17C9 19.2091 7.2091 21 5 21C2.7909 21 1 19.2091 1 17C1 14.7909 2.7909 13 5 13C7.2091 13 9 14.7909 9 17Z");
  stroke: none;
}

.lvbr6r3id {
  d: path("M8 7C8 8.6569 6.6569 10 5 10C3.3431 10 2 8.6569 2 7C2 5.3431 3.3431 4 5 4C6.6569 4 8 5.3431 8 7ZM8 17C8 18.6569 6.6569 20 5 20C3.3431 20 2 18.6569 2 17C2 15.3431 3.3431 14 5 14C6.6569 14 8 15.3431 8 17Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xdcgmbvng {
  stroke-opacity: 0.4;
  d: path("M12 7L22 7M12 17L22 17");
}

</style>
