<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzt0j5bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-not-allowed-fill-round" /></template>
<style>
.vzt0j5bya {
  fill: currentColor;
  d: path("M15.316 6.051a1 1 0 0 1-.073 1.919l-2.313.578a2.416 2.416 0 0 1-.223 3.159l-1 1a2.416 2.416 0 0 1-3.159.223l-.578 2.313a1 1 0 0 1-1.919.073l-4-12a1.001 1.001 0 0 1 1.265-1.265Zm4.239 7.117l.001.001h.001a4.606 4.606 0 1 1-5.108 7.665a4.606 4.606 0 0 1 5.105-7.667Zm-4.724 5.277l.002.003l2.67-4.005a2.606 2.606 0 0 0-2.672 4.002m4.336-2.893l-2.67 4.005l.003.001a2.605 2.605 0 0 0 2.667-4.006");
}

</style>
