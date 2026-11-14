<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4fx_nbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:high-voltage" /></template>
<style>
.a4fx_nbgr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.929 15.46l-4.994-8.804Q13.965 4.947 12 4.947T9.065 6.656L4.071 15.46q-.958 1.688.019 3.364T7.007 20.5h9.986q1.94 0 2.917-1.676t.019-3.364m-8.908-6.181q.528-.81 1.436-.477t.787 1.291l-.079.637q-.026.207.113.364q.138.157.348.157q.888.001 1.295.791t-.11 1.514l-1.924 2.694q-.54.753-1.4.408q-.861-.345-.729-1.264l.055-.388q.029-.2-.104-.352q-.132-.153-.334-.153q-.89 0-1.315-.783t.063-1.529z");
}

</style>
