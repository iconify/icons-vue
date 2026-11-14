<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xry4o31ih"/><path class="qx7dcyblo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fresh-pasta-pack" /></template>
<style>
.qx7dcyblo {
  d: path("M9 11.5a1.25 1.25 0 0 1 2.5 0a2.5 2.5 0 0 1-5 0a3.75 3.75 0 0 1 7.5 0m4 3.25v6.5m-2.75-4.75l5.5 3m-5.5 0l5.5-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xry4o31ih {
  d: path("M12.856 21H6q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132q-.07-.069-.132-.145t-.117-.158t-.101-.168t-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T4 19V5l2-2l2 2l2-2l2 2l2-2l2 2l2-2l2 2v6.973");
}

</style>
