<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u56efebob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:decanter" /></template>
<style>
.u56efebob {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 2.25h2.5q2 0 2 2q0 1-.5 1.5v2.472q3.084 1.218 4.143 4.466q1.146 3.514-1.026 6.505T12 22.185t-5.867-2.992q-2.172-2.991-1.026-6.505Q6.166 9.44 9.25 8.222V5.75q-.5-.5-.5-1.5q0-2 2-2m0 4v2.5q0 .059-.009.117q-.01.059-.028.115t-.045.109t-.062.1t-.076.09t-.09.076q-.048.035-.1.062t-.109.045q-2.789.902-3.698 3.689t.814 5.159Q9.069 20.685 12 20.685t4.653-2.373t.814-5.159t-3.698-3.689q-.056-.019-.109-.045q-.052-.027-.1-.062q-.048-.034-.09-.076t-.076-.09t-.062-.1q-.027-.053-.045-.109t-.028-.115t-.009-.117v-2.5z");
}

</style>
