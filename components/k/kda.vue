<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGqZUiXdBY)" class="a5ydl5j7w"/><path class="v-yfieurd"/><path fill="url(#SVGq7ydtbFw)" class="v0kqgdbeo"/><defs><linearGradient id="SVGqZUiXdBY" x1="16.43" x2="7.141" y1="21" y2="7.898" gradientUnits="userSpaceOnUse"><stop class="yjmxllbqh"/><stop offset="1" class="pqh-fcc8a"/></linearGradient><linearGradient id="SVGq7ydtbFw" x1="17.706" x2="7.581" y1="3" y2="12.281" gradientUnits="userSpaceOnUse"><stop class="he1v5tbxk"/><stop offset="1" class="oxn57eb_m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kda" /></template>
<style>
.a5ydl5j7w {
  d: path("M20.357 21h-5.571L9.07 12.857l2.286-4.714z");
}

.ft5dv1b6b {
  fill: none;
}

.he1v5tbxk {
  stop-color: var(--svg-color--730196, #730196);
}

.oxn57eb_m {
  stop-color: var(--svg-color--ed098f, #ed098f);
}

.pqh-fcc8a {
  stop-color: var(--svg-color--e40790, #e40790);
}

.v-yfieurd {
  fill: var(--svg-color--6a0097, #6a0097);
  d: path("M3.643 3h4.5v18h-4.5z");
}

.v0kqgdbeo {
  d: path("M19.357 3h-5.142L8.143 9.187v5.623z");
}

.yjmxllbqh {
  stop-color: var(--svg-color--6a0097, #6a0097);
}

</style>
