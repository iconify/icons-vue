<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ul9eysb-h"/><circle class="rzyzgqcqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bahai-star-sharp" /></template>
<style>
.rzyzgqcqn {
  cx: 12px;
  cy: 12px;
  r: 2.25px;
}

.ul9eysb-h {
  d: path("m12.3 3.27l1.46 2.57l.29.52l.56-.21l2.77-1.03l.57-.21l-.11.59l-.54 2.91l-.1.59l.56.2l2.78.99l.57.2l-.46.39l-2.28 1.88l-.46.38l.3.52l1.5 2.55l.3.52l-.6-.01l-2.95-.02h-.6l-.1.59l-.5 2.91l-.1.59l-.45-.39l-2.25-1.91L12 18l-.46.39l-2.25 1.91l-.45.39l-.1-.59l-.5-2.91l-.1-.59h-.6l-2.95.02l-.6.01l.3-.52l1.5-2.55l.3-.52l-.46-.38l-2.28-1.88l-.46-.39l.57-.2l2.78-.99l.56-.2l-.1-.59l-.54-2.91l-.11-.59l.57.21l2.77 1.03l.56.21l.29-.52l1.46-2.57l.3-.52z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
