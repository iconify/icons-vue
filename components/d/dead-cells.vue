<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="re8w2z3mj"/><path class="ywv1x7hqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dead-cells" /></template>
<style>
.re8w2z3mj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.832 3.5c-8.902.68-13.353 9.373-10.944 16.704c8.273-.131 12.358 12.043 5.148 12.043c0 5.865 3.125 12.253 10.09 12.253s9.634-5.97 9.634-10.21c0-10.002-9.32-9.61-10.682-16.757c-4.45 3.351-12.933-5.184-3.246-14.033");
}

.ywv1x7hqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.356 14.26c-2.369 2.641-.666 8.417 2.246 8.417c1.506 0 2.32-.963 2.32-2.172c0-2.814-4.516-1.234-4.566-6.244m2.289 18.955c-4.74-.284-5.787-2.063-6.127-8.51c-.34 6.447-1.387 8.226-6.126 8.51c4.739.283 5.786 2.063 6.126 8.509c.34-6.447 1.388-8.226 6.127-8.51");
}

</style>
