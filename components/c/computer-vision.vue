<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a281agbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:computer-vision" /></template>
<style>
.a281agbkc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.804 11.721Q4.992 3.75 12 3.75t10.196 7.971q.054.135.054.279t-.054.279Q19.008 20.25 12 20.25T1.804 12.279Q1.75 12.144 1.75 12t.054-.279M10.875 7.5Q7.5 7.5 7.5 10.875v2.25q0 3.375 3.375 3.375h2.25q3.375 0 3.375-3.375v-2.25q0-3.375-3.375-3.375z");
}

</style>
