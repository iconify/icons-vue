<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpkftmbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:clay-tablet" /></template>
<style>
.rpkftmbqf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.748 2.049l-4.209.591q-2.103.296-3.38 1.992q-1.278 1.695-.982 3.797l1.287 9.16q.296 2.102 1.991 3.38q1.695 1.277 3.797.982l4.209-.591q2.103-.296 3.38-1.992q1.278-1.695.982-3.797l-1.287-9.16q-.296-2.102-1.991-3.38q-1.695-1.277-3.797-.982M7.13 7.887q-.116-.831.446-1.453t1.4-.591l2.304.085q1.158.043 1.32 1.191q.161 1.148-.941 1.509l-2.191.717q-.797.26-1.509-.183q-.712-.444-.829-1.274zm1.123 3.26q.578-.611 1.416-.54l1.564.131q1.106.092 1.261 1.192t-.883 1.494l-1.467.558q-.787.299-1.511-.129q-.725-.428-.842-1.262q-.116-.833.462-1.444m.199 6.148q-.116-.83.445-1.453q.562-.623 1.401-.592l2.304.086q1.158.043 1.32 1.191q.161 1.148-.941 1.509l-2.191.717q-.797.26-1.509-.183q-.712-.444-.829-1.274z");
}

</style>
