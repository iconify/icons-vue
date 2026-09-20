<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r8gz0acfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-vscode2" /></template>
<style>
.r8gz0acfi {
  fill: var(--svg-color--007acc, #007acc);
  d: path("m11.72 18.685l-6.883 5.184L2 22.922L9 16L2 9.077l2.837-.947l6.883 5.184l11.433-11.3L30 4.922v22.155l-6.847 2.909ZM15.287 16l7.865 5.923V10.076Z");
}

</style>
