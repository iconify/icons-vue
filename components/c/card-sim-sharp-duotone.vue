<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k-43mob3m"/><path class="stvgvsbre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:card-sim-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k-43mob3m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 1L14 1C14.2652 1 14.5196 1.1054 14.7071 1.2929L19.7071 6.2929C19.8946 6.4804 20 6.7348 20 7L20 22C20 22.5523 19.5523 23 19 23L5 23C4.4477 23 4 22.5523 4 22L4 2C4 1.4477 4.4477 1 5 1Z");
}

.stvgvsbre {
  d: path("M9 11L15 11C15.5523 11 16 11.4477 16 12L16 18C16 18.5523 15.5523 19 15 19L9 19C8.4477 19 8 18.5523 8 18L8 12C8 11.4477 8.4477 11 9 11Z");
}

</style>
