<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8_98jb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:armrest" /></template>
<style>
.j8_98jb5o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 1.75h-3.5q-2.25 0-2.25 2.25v4.326q-.337-.076-.75-.076H7q-2.25 0-2.25 2.25T7 12.75h4.5q.413 0 .75-.076v1.576H5q-2.25 0-2.25 2.25V19q0 2.25 2.25 2.25h12q2.237 0 2.25-2.224l.998-14.976l.002-.05q0-2.25-2.25-2.25");
}

</style>
