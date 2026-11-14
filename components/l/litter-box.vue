<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xck7jqble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:litter-box" /></template>
<style>
.xck7jqble {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 9.25h-8.525q-1.656-3.311-4.631-3.187q-2.908.121-3.909 3.187H2.5q-.081 0-.16.017q-.146.032-.268.117t-.203.211t-.107.273q-.027.147.005.292l1.75 8q.014.062.038.122q.024.059.057.113q.034.054.076.102t.092.087q.049.04.105.071t.116.052q.06.022.123.032q.062.011.126.011h15.5q.064 0 .126-.011q.063-.01.123-.032t.116-.052t.105-.071q.05-.04.092-.087q.042-.048.076-.102t.057-.113q.024-.06.038-.122l1.75-8q.017-.079.017-.16q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014M8.406 7.562Q6.778 7.63 6.045 9.25h5.206q-1.144-1.759-2.845-1.688");
}

</style>
