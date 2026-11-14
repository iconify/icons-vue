<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu-m2kb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:frozen-waterfall" /></template>
<style>
.zu-m2kb9i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 2.25h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q1.75 2.926 1.75 3t.014.146t.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h.581q-.173.486-.098 1.047l.774 5.803q.205 1.525 1.743 1.525t1.743-1.526l.774-5.802q.075-.561-.098-1.047h1.626q-.165.464-.105.999l.814 7.333q.172 1.564 1.746 1.564t1.745-1.563l.815-7.334q.06-.535-.105-.999h1.662q-.182.507-.092 1.092l.734 4.773q.232 1.492 1.741 1.492t1.741-1.493l.734-4.772q.09-.585-.092-1.092h.617q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T22.25 3t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
