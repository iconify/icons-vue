<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbp4bublo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:browse-activity-rounded" /></template>
<style>
.rbp4bublo {
  fill: currentColor;
  d: path("M2.27 19.462q-.214 0-.358-.144t-.143-.356t.144-.357t.356-.144h19.462q.213 0 .356.144t.144.356t-.144.357t-.356.144zm2.346-2q-.691 0-1.153-.463T3 15.846v-4.884h4.683l1.86 3.719q.067.135.189.208t.262.073t.266-.068t.192-.202l3.498-6.201l1.016 2.017q.105.217.307.335t.42.119H21v4.884q0 .69-.462 1.153t-1.153.463zm5.459-3.99l-1.617-3.23q-.067-.134-.192-.207T8 9.962H3V6.077q0-.69.463-1.153t1.152-.462h14.77q.69 0 1.152.462T21 6.077v3.885h-5.183l-1.36-2.72q-.066-.14-.191-.191T14 7t-.26.051t-.186.18z");
}

</style>
