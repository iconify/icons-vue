<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="isezuxbwc"/><path class="qfkmyab4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-lock-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.isezuxbwc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 11h-6v6a1 1 0 0 1-1 1a8 8 0 1 1 3.064-15.39A7.99 7.99 0 0 1 18 10a1 1 0 0 1-1 1");
}

.qfkmyab4s {
  d: path("M8.029 9h3.942c-.066-1.152-.245-2.378-.655-3.457c-.169-.443-.382-.899-.718-1.242C10.439 4.139 10.235 4 10 4s-.439.139-.598.301c-.336.343-.549.799-.718 1.242c-.41 1.079-.589 2.305-.655 3.457m-2.003 2H3a1 1 0 0 1 0-2h3.026c.072-1.399.29-2.857.79-4.168c.267-.702.628-1.389 1.157-1.93C8.521 2.343 9.209 2 10 2s1.479.343 2.027.902c.529.541.89 1.228 1.157 1.93c.5 1.311.718 2.769.79 4.168H17a1 1 0 0 1 0 2H8.029c.066 1.152.245 2.378.655 3.457c.169.443.382.899.718 1.242c.159.162.363.301.598.301a1 1 0 0 1 0 2c-.791 0-1.479-.343-2.027-.902c-.529-.541-.89-1.228-1.157-1.93c-.5-1.311-.718-2.769-.79-4.168M15 17a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1Zm5-1.829A3 3 0 0 1 22 18v1a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3v-1c0-1.27.803-2.405 2-2.829V15a3 3 0 1 1 6 0ZM16 15h2a1 1 0 0 0-2 0");
}

</style>
