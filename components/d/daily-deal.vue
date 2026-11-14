<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bn4cd6iwp"/><path class="gmhdbo8hv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:daily-deal" /></template>
<style>
.bn4cd6iwp {
  d: path("M12.828 21H6q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132q-.07-.069-.132-.145t-.117-.158t-.101-.168t-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T4 19V5l2-1.5L8 5l2-1.5L12 5l2-1.5L16 5l2-1.5L20 5v5.7M4 8.5h16");
}

.gmhdbo8hv {
  d: path("M7 11.5h4v4H7Zm6.5 6.25l4.25-4.25H22v4.25L17.75 22Zm6.25-2h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
