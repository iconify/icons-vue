<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="b6c56u_4b"/><ellipse class="axe42k4fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:dotted-six-pointed-star" /></template>
<style>
.axe42k4fu {
  cx: 32px;
  cy: 32px;
  fill: currentColor;
  rx: 4.199px;
  ry: 4.286px;
}

.b6c56u_4b {
  fill: currentColor;
  d: path("M50.262 32L60 16H40.522L32 2l-8.521 14H4l9.739 16L4 48h19.479L32 62l8.522-14H60zm.459-11l-3.547 5.928L43.566 21zm-6.58 11l-6.578 11H26.439l-6.578-11l6.578-11h11.123zM32 11.701L34.572 16H29.43zM13.283 21h7.151l-3.607 5.926zm0 22l3.544-5.926L20.435 43zM32 52.299L29.43 48h5.143zm15.174-15.227L50.721 43h-7.154z");
}

</style>
