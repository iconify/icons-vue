<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot4fbk_po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-clover-four" /></template>
<style>
.ot4fbk_po {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.981 5.981q-1.268-.097-2.45.691Q3.75 7.859 3.75 10t1.781 3.328q1.182.788 2.45.691q-.097 1.268.691 2.45q.982 1.473 2.617 1.728q.279 2.417 2.545 3.927q.061.041.13.069q.068.028.14.043t.147.014q.074 0 .146-.015q.073-.014.141-.042t.129-.07t.114-.093q.052-.053.093-.114t.069-.13t.043-.14q.014-.073.014-.147t-.015-.146q-.014-.073-.042-.141t-.07-.129t-.093-.114q-.053-.052-.114-.093q-1.594-1.063-1.862-2.695q1.57-.281 2.524-1.712q.788-1.182.691-2.45q1.268.097 2.45-.691Q20.25 12.141 20.25 10t-1.781-3.328q-1.182-.788-2.45-.691q.097-1.268-.691-2.45Q14.141 1.75 12 1.75T8.672 3.531q-.788 1.182-.691 2.45");
}

</style>
