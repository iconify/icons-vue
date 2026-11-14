<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btq_4mbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:beetroot" /></template>
<style>
.btq_4mbjp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.071 6.692q.646.559 1.463.918q-.888.491-1.661 1.263Q4.75 10.997 4.75 14q0 3.41 4.687 5.842q1.678.871 1.912 1.28q.101.178.279.279q.129.074.277.093t.292-.02q.144-.04.262-.131t.192-.221q.234-.409 1.912-1.28Q19.25 17.41 19.25 14q0-3.003-2.123-5.127q-.773-.772-1.661-1.263q.817-.359 1.463-.918q1.812-1.571 1.299-3.624q-.016-.06-.04-.117q-.025-.058-.059-.11t-.076-.098t-.091-.084t-.104-.068t-.114-.05t-.12-.031q-.062-.01-.124-.01q-4.085 0-5.5 2.136Q10.585 2.5 6.5 2.5q-.062 0-.124.01q-.061.011-.12.031t-.114.05t-.104.068t-.091.084t-.076.098t-.059.11q-.024.057-.04.117q-.513 2.053 1.299 3.624");
}

</style>
