<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj7g8mbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:band-sync" /></template>
<style>
.kj7g8mbao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 17.5H4v-12h11.5v7.9M7.25 5.5v-2a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v2m-5 12v3q0 .098.019.195t.057.188t.093.173q.054.081.124.151t.151.124q.082.055.173.093t.188.057t.195.019h3q.077 0 .152-.012q.076-.011.149-.034t.141-.057t.132-.078q.062-.044.118-.097t.101-.113q.047-.061.084-.128t.063-.139M15 16.25h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

</style>
