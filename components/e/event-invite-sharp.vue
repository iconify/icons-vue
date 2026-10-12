<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bnr1nsbob"/><path class="pl8y3ac9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:event-invite-sharp" /></template>
<style>
.bnr1nsbob {
  d: path("M2.75 9.25h18.5v12H2.75z");
}

.pl8y3ac9f {
  d: path("M3.5 10.5L12 16l8.5-5.5M12 2.75l.33 2.42l2.42.33l-2.42.33L12 8.25l-.33-2.42l-2.42-.33l2.42-.33z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
