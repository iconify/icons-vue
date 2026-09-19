<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nzr42g0zf"/><ellipse transform="rotate(159.298 21.114 51.532)" class="fkztrew0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:droplet" /></template>
<style>
.fkztrew0x {
  cx: 21.11px;
  cy: 51.53px;
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  rx: 4.296px;
  ry: 6.719px;
}

.nzr42g0zf {
  fill: var(--svg-color--57c6e9, #57c6e9);
  d: path("M35.898 3.677C34.224-.55 29.041-2.087 24.72 5.419s-30.354 42.994.976 56.875c11.538 5.292 25.322-2.938 27.353-12.245c3.627-16.611-11.161-31.25-17.15-46.37");
}

</style>
