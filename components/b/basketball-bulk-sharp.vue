<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="a4_98suhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:basketball-bulk-sharp" /></template>
<style>
.a4_98suhf {
  d: path("M13 11h2.045c.185-2.028.934-3.97 2.155-5.6a1 1 0 1 1 1.6 1.2a9 9 0 0 0-1.745 4.4H21a1 1 0 0 1 0 2h-3.945a9 9 0 0 0 1.745 4.4a1 1 0 0 1-1.6 1.2a11 11 0 0 1-2.155-5.6H13v8a1 1 0 0 1-2 0v-8H8.955a11 11 0 0 1-.52 2.479A10.9 10.9 0 0 1 6.8 18.6a1 1 0 0 1-1.6-1.2a9 9 0 0 0 1.338-2.554c.2-.599.337-1.218.407-1.846H3a1 1 0 0 1 0-2h3.945A9 9 0 0 0 5.2 6.6a1 1 0 0 1 1.6-1.2A11 11 0 0 1 8.955 11H11V3a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
