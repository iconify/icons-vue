<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r6xsfz4lg"/><circle class="pw_u43c3e"/><path class="yycu1e_9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:employee-handbook-sharp" /></template>
<style>
.pw_u43c3e {
  cx: 12px;
  cy: 9.75px;
  r: 3.5px;
}

.r6xsfz4lg {
  d: path("M4.75 18.75v-16h14.5v13.5H4.75v2Zm0 0v2.5h14.5v-4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yycu1e_9d {
  d: path("M12 9.5v2m0-3.75v.01");
}

</style>
