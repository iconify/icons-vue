<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":98};
const content = `<path class="mp2wqsbih"/><path class="r_ggsrbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:eraser-icon" /></template>
<style>
.mp2wqsbih {
  fill: var(--svg-color--eb043b, #eb043b);
  d: path("M121.5 97.041H7.542c-5.844 0-9.466-8.093-6.461-14.424l37.08-77.97C39.56 1.764 41.989 0 44.664 0h76.838z");
}

.r_ggsrbcy {
  fill: var(--svg-color--0085ff, #0085ff);
  d: path("M134.54 0h113.92c5.843 0 9.464 8.093 6.46 14.424l-37.081 77.97c-1.357 2.844-3.826 4.607-6.461 4.607H134.54z");
}

</style>
