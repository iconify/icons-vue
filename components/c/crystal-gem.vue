<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf32g-biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crystal-gem" /></template>
<style>
.cf32g-biz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.673 2.997l3.25 2.925q.199.179.35.379q-.133-.052-.276-.051t-.276.054L12 8.192L7.279 6.304q-.133-.053-.276-.054t-.276.051q.151-.2.35-.379l3.25-2.925q1.673-1.507 3.346 0m4.016 4.298l.013-.031q.048.247.048.515v8.442q0 1.113-.827 1.857l-3.25 2.925q-.466.419-.931.605q.008-.054.008-.108V9.508l4.529-1.812q.138-.055.245-.159t.165-.242M11.25 9.508L6.721 7.696q-.146-.058-.257-.171q-.11-.113-.166-.261q-.048.247-.048.515v8.442q0 1.113.827 1.857l3.25 2.925q.466.419.931.605q-.008-.054-.008-.108z");
}

</style>
