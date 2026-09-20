<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hw_0_jytq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-hint-half-vertical-16-regular" /></template>
<style>
.hw_0_jytq {
  fill: currentColor;
  d: path("M8.05 1q.794.002 1.538.17a.474.474 0 0 1 .323.652a.54.54 0 0 1-.613.309a6 6 0 1 0-.032 11.744a.535.535 0 0 1 .62.338a.475.475 0 0 1-.337.625A7 7 0 1 1 8.05 1m4.975 10.35a.535.535 0 0 1 .693-.184a.473.473 0 0 1 .182.675a7 7 0 0 1-2.176 2.115a.475.475 0 0 1-.696-.266a.54.54 0 0 1 .232-.622a6 6 0 0 0 1.765-1.717m1.252-5.155a.474.474 0 0 1 .619.341a7 7 0 0 1-.053 3.152a.475.475 0 0 1-.695.29a.54.54 0 0 1-.257-.6a6 6 0 0 0 .04-2.563a.535.535 0 0 1 .346-.62m-3.21-3.897a.475.475 0 0 1 .689-.236a7 7 0 0 1 2.268 2.293c.162.264.02.6-.273.696a.54.54 0 0 1-.615-.236a6 6 0 0 0-1.85-1.868a.54.54 0 0 1-.219-.65");
}

</style>
