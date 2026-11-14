<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plx3krbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ammo-box" /></template>
<style>
.plx3krbam {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 3.75h15q2.75 0 2.75 2.75q0 1.658-1 2.317V18q0 2.25-2.25 2.25H5q-2.25 0-2.25-2.25V8.817q-1-.659-1-2.317q0-1.139.805-1.945q.806-.805 1.945-.805m13.25 15H19q.75 0 .75-.75V9.244q-.122.006-.25.006h-1.75zm-1.5-9.5h-2v2.25q0 2.25-2.25 2.25T9.75 11.5V9.25h-2v9.5h8.5zm-10 9.5v-9.5H4.5q-.128 0-.25-.006V18q0 .75.75.75zm6.5-9.5h-1.5v2.25q0 .75.75.75t.75-.75z");
}

</style>
