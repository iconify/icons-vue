<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b58d_pb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ceiling-fan-blades" /></template>
<style>
.b58d_pb6l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.407 3.889l2.455 4.464Q11.38 8.25 12 8.25t1.138.103l2.455-4.464q.078-.142.207-.239q2.255-1.691 4.248.302T20.35 8.2q-.097.129-.239.207l-4.464 2.455q.103.518.103 1.138t-.103 1.138l4.464 2.455q.142.078.239.207q1.691 2.255-.302 4.248t-4.248.302q-.129-.097-.207-.239l-2.455-4.464q-.518.103-1.138.103t-1.138-.103l-2.455 4.464q-.078.142-.207.239q-2.255 1.691-4.248-.302T3.65 15.8q.097-.129.239-.207l4.464-2.455Q8.25 12.62 8.25 12t.103-1.138L3.889 8.407q-.142-.078-.239-.207q-1.691-2.255.302-4.248T8.2 3.65q.129.097.207.239");
}

</style>
