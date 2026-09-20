<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm_h46b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hdr-auto" /></template>
<style>
.qm_h46b2n {
  fill: currentColor;
  d: path("M6.9 17h1.9l1-2.8h4.4l1 2.8h1.9L13 6h-2zm3.45-4.4l1.6-4.55h.1l1.6 4.55zM12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
