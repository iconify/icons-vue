<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oium3sz0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-off-fill-sharp" /></template>
<style>
.oium3sz0n {
  fill: currentColor;
  d: path("m3.707 1.293l19 19a.999.999 0 1 1-1.414 1.414L17.586 18H16a4 4 0 0 1-8 0H4a1 1 0 0 1-1-1v-2c0-.39.098-.773.299-1.108c.133-.222.312-.417.494-.599c.065-.066.145-.133.193-.214C4 13.057 4 13.026 4 13v-3c0-1.533.436-3.031 1.265-4.321L2.293 2.707a.999.999 0 1 1 1.414-1.414m5.992 3.164L8.2 2.958A8 8 0 0 1 20 10v3c0 .026 0 .057.014.079c.048.081.128.148.193.214c.182.182.361.377.494.599c.201.335.299.718.299 1.108v.757Z");
}

</style>
