<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpv4mkowi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gift-tier-gold" /></template>
<style>
.bpv4mkowi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 4.5h10.5q3 0 3 3q0 .879-.257 1.5h.257q3 0 3 3q0 2.614-2.278 2.95q.278.636.278 1.55q0 3-3 3H6.25q-3 0-3-3q0-2.614 2.278-2.95q-.278-.636-.278-1.55q0-.831.393-1.5H5.25q-1.243 0-2.121-.879Q2.25 8.743 2.25 7.5t.879-2.121Q4.007 4.5 5.25 4.5");
}

</style>
