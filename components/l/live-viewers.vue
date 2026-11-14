<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwbpf5wqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:live-viewers" /></template>
<style>
.cwbpf5wqy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 3.75h8.5q2.485 0 4.243 1.757Q22.25 7.265 22.25 9.75v4.5q0 2.485-1.757 4.243q-1.758 1.757-4.243 1.757h-8.5q-2.485 0-4.243-1.757Q1.75 16.735 1.75 14.25v-4.5q0-2.485 1.757-4.243Q5.265 3.75 7.75 3.75M12 7.5q-3.675 0-6.143 4.114q-.053.088-.08.186t-.027.2t.027.2t.08.186Q8.325 16.5 12 16.5t6.143-4.114q.053-.088.08-.186t.027-.2t-.027-.2t-.08-.186Q15.675 7.5 12 7.5");
}

</style>
