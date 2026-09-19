<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1wmfxbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-blender" /></template>
<style>
.s1wmfxbaf {
  fill: currentColor;
  d: path("M16.13 15.13L18 3h-4V2h-4v1H5c-1.1 0-2 .9-2 2v4c0 1.1.9 2 2 2h2.23l.64 4.13C6.74 16.05 6 17.43 6 19v1c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2v-1c0-1.57-.74-2.95-1.87-3.87M5 9V5h1.31l.62 4zm7 10c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m2.29-5H9.72L8.33 5h7.34z");
}

</style>
