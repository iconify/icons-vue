<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i_bck_mlj"/><path clip-rule="evenodd" class="ilki4vb1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-space-between-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i_bck_mlj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 6V7C6 8.6569 7.343 10 9 10H15C16.657 10 18 8.6569 18 7V6C18 4.3431 16.657 3 15 3H9C7.343 3 6 4.3431 6 6ZM6 18V17C6 15.3431 7.343 14 9 14H15C16.657 14 18 15.3431 18 17V18C18 19.6569 16.657 21 15 21H9C7.343 21 6 19.6569 6 18Z");
}

.ilki4vb1i {
  fill-rule: evenodd;
  d: path("M1 4C1 4.5523 1.448 5 2 5H22C22.552 5 23 4.5523 23 4C23 3.4477 22.552 3 22 3H2C1.448 3 1 3.4477 1 4ZM1 20C1 20.5523 1.448 21 2 21H22C22.552 21 23 20.5523 23 20C23 19.4477 22.552 19 22 19H2C1.448 19 1 19.4477 1 20Z");
}

</style>
