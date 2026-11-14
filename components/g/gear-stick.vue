<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw0wxs4mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gear-stick" /></template>
<style>
.lw0wxs4mp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 6.5q0-1.864 1.318-3.182T12 2t3.182 1.318T16.5 6.5t-1.318 3.182q-1.045 1.045-2.432 1.261v5.307h.537q1.733 0 2.341 1.623l.324.864q.411 1.093-.255 2.053t-1.833.96h-3.728q-1.168 0-1.833-.96q-.666-.96-.255-2.053v-.001l.324-.863q.608-1.623 2.341-1.623h.537v-5.307q-1.387-.216-2.432-1.261Q7.5 8.364 7.5 6.5");
}

</style>
