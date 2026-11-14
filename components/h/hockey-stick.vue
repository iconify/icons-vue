<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1x224bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hockey-stick" /></template>
<style>
.i1x224bhx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.181 2.814l-7.5 16.25l-.019.039Q10.783 20.75 9 20.75H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.25 20t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T4 19.25h5q.874 0 1.329-.835l7.49-16.229q.063-.136.172-.237q.11-.101.25-.153t.289-.045t.284.068q.067.031.127.074q.06.044.11.098t.089.117t.064.133t.037.142t.008.147t-.02.145q-.017.072-.048.139");
}

</style>
