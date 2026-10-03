<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vgu6gkkjs"/><path clip-rule="evenodd" class="k_6bd8c7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:container-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k_6bd8c7k {
  fill-rule: evenodd;
  d: path("M1 11C1 9.3431 2.3431 8 4 8L16 8C17.6569 8 19 9.3431 19 11L19 17C19 18.6569 17.6569 20 16 20L4 20C2.3431 20 1 18.6569 1 17L1 11ZM5 10L5 18L7 18L7 10L5 10ZM9 10L9 18L11 18L11 10L9 10ZM13 10L13 18L15 18L15 10L13 10Z");
}

.vgu6gkkjs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 20C2.3431 20 1 18.6569 1 17L1 11C1 10.2044 1.3161 9.4413 1.8787 8.8787L5.8787 4.8787C6.4413 4.3161 7.2044 4 8 4L20 4C21.6569 4 23 5.3431 23 7L23 13C23 13.7956 22.6839 14.5587 22.1213 15.1213L18.1213 19.1213C17.5587 19.6839 16.7956 20 16 20L4 20Z");
}

</style>
