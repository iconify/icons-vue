<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rdhq0wbff"/><path clip-rule="evenodd" class="o_4gopxmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o_4gopxmc {
  fill-rule: evenodd;
  d: path("M9 20L9 18C9 16.3431 10.3431 15 12 15C13.6569 15 15 16.3431 15 18L15 20L9 20Z");
}

.rdhq0wbff {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.0604 2.70725C11.1794 1.75935 12.8203 1.75928 13.9393 2.70725L22.6463 10.0842C23.0676 10.4412 23.1194 11.072 22.7625 11.4934C22.4056 11.9147 21.7747 11.9674 21.3533 11.6106L20.9998 11.3108V19.0002C20.9996 20.6569 19.6566 22.0002 17.9998 22.0002H5.99983C4.34311 22.0002 3.00008 20.6569 2.99983 19.0002V11.3108L2.64632 11.6106C2.22495 11.9675 1.59412 11.9147 1.23714 11.4934C0.880186 11.072 0.931985 10.4412 1.35335 10.0842L10.0604 2.70725Z");
}

</style>
