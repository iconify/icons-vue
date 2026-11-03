<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pizqdx4nh"/><path clip-rule="evenodd" class="o_4gopxmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-chimney-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o_4gopxmc {
  fill-rule: evenodd;
  d: path("M9 20L9 18C9 16.3431 10.3431 15 12 15C13.6569 15 15 16.3431 15 18L15 20L9 20Z");
}

.pizqdx4nh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.3857 2.20711C11.7469 1.92603 12.253 1.92603 12.6142 2.20711L15 4.06257V3.00007C15 2.4478 15.4477 2.00009 16 2.00007H20C20.5522 2.00007 21 2.44779 21 3.00007V8.7325L23 10.2891L21.7714 11.8673L21 11.2667V21.0001C20.9998 21.5522 20.5521 22.0001 20 22.0001H3.99996C3.44781 22.0001 3.00014 21.5522 2.99996 21.0001V11.2667L2.22848 11.8673L0.999962 10.2891L11.3857 2.20711Z");
}

</style>
