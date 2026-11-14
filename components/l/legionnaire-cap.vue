<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qoauxabtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:legionnaire-cap" /></template>
<style>
.qoauxabtk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.665 6.15Q4.272 8.766 4.25 13.414l-1.481 6.417q-.033.146-.009.293q.025.147.104.273t.201.214q.121.086.266.12q.13.03.262.013l8-1q.067-.008.132-.029q.065-.02.125-.052t.114-.074t.098-.093t.08-.109t.059-.122q.025-.063.037-.13T12.25 19v-4.75h9.25q.107 0 .211-.03q.103-.03.193-.088t.161-.139t.116-.179q.062-.135.068-.284t-.045-.289t-.153-.25t-.237-.172l-2.82-1.302Q18.8 3.75 12.25 3.75q-3.389 0-5.585 2.4M4.472 19.123l1.125-4.873h5.153v4.088z");
}

</style>
