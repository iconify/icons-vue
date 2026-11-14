<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72zbacef"/><path class="hjrc0fb7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electric-bill" /></template>
<style>
.hjrc0fb7z {
  d: path("M11.866 6.561L9.8 9.04a.585.585 0 0 0 .45.96a.976.976 0 0 1 .947 1.213l-.072.287a.382.382 0 0 0 .656.348l2.386-2.666a.559.559 0 0 0-.417-.932a1.14 1.14 0 0 1-1.137-1.245l.012-.13a.43.43 0 0 0-.759-.314M8 15.75h8M8 18.5h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o72zbacef {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5");
}

</style>
