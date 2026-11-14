<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afbo1lb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:design-pattern" /></template>
<style>
.afbo1lb0y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 1.75h.75q3.182 0 3.364 3h5.522q.182-3 3.364-3h.75q3.375 0 3.375 3.375v.75q0 3.182-3 3.364v5.522q3 .182 3 3.364v.75q0 3.375-3.375 3.375h-.75q-3.182 0-3.364-3H9.239q-.182 3-3.364 3h-.75q-3.375 0-3.375-3.375v-.75q0-3.182 3-3.364V9.239q-3-.182-3-3.364v-.75q0-3.375 3.375-3.375M6.25 9.239v5.522q2.818.171 2.989 2.989h5.522q.171-2.818 2.989-2.989V9.239q-2.818-.171-2.989-2.989H9.239Q9.068 9.068 6.25 9.239");
}

</style>
