<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="c7uq-7bis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fossil-sharp" /></template>
<style>
.c7uq-7bis {
  d: path("M12 11c.14-.01.55-.17.83-.08l.578.193l.252.447l.361.621l-.101.619l-.137.821l-.563.489l-.726.63l-.864.03l-1.089.038l-.771-.578l-.967-.707l-.293-1.063l-.335-1.304l.465-1.096l.592-1.351l1.148-.619l1.377-.761l1.433.231l1.652.269L15.93 8.98l1.239 1.329L17.31 12l.179 1.928l-.989 1.522l-1.13 1.74l-1.81.64l-2.067.713L9.55 17.9c-1.23-.4-2.83-2.1-3.4-2.53");
}

.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
