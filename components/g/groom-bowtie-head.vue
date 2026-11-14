<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8_t44bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:groom-bowtie-head" /></template>
<style>
.o8_t44bjx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.757 4.007Q6 5.765 6 8.25t1.757 4.243Q9.515 14.25 12 14.25t4.243-1.757Q18 10.735 18 8.25t-1.757-4.243Q14.485 2.25 12 2.25T7.757 4.007m8.908 18.164L12 19.839l-4.665 2.332q-.158.079-.335.079q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-5q0-.177.079-.335q.033-.066.079-.125q.045-.058.101-.107q.055-.048.12-.085q.064-.036.134-.06q.07-.023.143-.032t.147-.004t.145.025t.137.052L12 18.161l4.665-2.332q.066-.033.137-.052q.071-.02.145-.025t.147.004t.143.032t.134.06t.12.085t.101.107t.079.125q.079.158.079.335v5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.177 0-.335-.079");
}

</style>
