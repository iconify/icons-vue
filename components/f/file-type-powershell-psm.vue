<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGrKDJOnCC" x1="23.325" x2="7.26" y1="-118.543" y2="-104.193" gradientTransform="matrix(1 0 0 -1 0 -96)" gradientUnits="userSpaceOnUse"><stop offset="0" class="i3-xs-y7p"/><stop offset="1" class="ucnyhobmi"/></linearGradient><linearGradient id="SVGBHYpsbuH" x1="7.1" x2="23.001" y1="-104.002" y2="-118.292" gradientTransform="matrix(1 0 0 -1 0 -96)" gradientUnits="userSpaceOnUse"><stop offset="0" class="i3-xs-y7p"/><stop offset="1" class="bh6dg9baa"/></linearGradient></defs><path fill="url(#SVGrKDJOnCC)" class="rtj_6o5oh"/><path fill="url(#SVGBHYpsbuH)" class="dooz00i_y"/><path class="vek9tzf5v"/><path class="zomopvbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-powershell-psm" /></template>
<style>
.bh6dg9baa {
  stop-color: var(--svg-color--ba3fba, #ba3fba);
}

.dooz00i_y {
  fill-rule: evenodd;
  d: path("M7.914 5.646h20.912a.913.913 0 0 1 .908 1.187l-4.2 18.334a1.575 1.575 0 0 1-1.451 1.187H3.174a.913.913 0 0 1-.908-1.187l4.2-18.334a1.57 1.57 0 0 1 1.448-1.187");
}

.i3-xs-y7p {
  stop-color: var(--svg-color--f955f9, #f955f9);
}

.rtj_6o5oh {
  fill-rule: evenodd;
  d: path("M3.174 26.589a1.15 1.15 0 0 1-.928-.423a1.23 1.23 0 0 1-.21-1.052L6.233 6.78a1.8 1.8 0 0 1 1.681-1.37h20.912a1.16 1.16 0 0 1 .928.423a1.24 1.24 0 0 1 .21 1.052l-4.2 18.335a1.8 1.8 0 0 1-1.681 1.37H3.174Z");
}

.ucnyhobmi {
  stop-color: var(--svg-color--ad44ad, #ad44ad);
}

.vek9tzf5v {
  fill: var(--svg-color--8c2d8a, #8c2d8a);
  fill-rule: evenodd;
  d: path("M16.04 21.544h5.086a1.118 1.118 0 0 1 0 2.234H16.04a1.118 1.118 0 0 1 0-2.234m3.299-4.966a1.76 1.76 0 0 1-.591.6l-9.439 6.775a1.224 1.224 0 0 1-1.438-1.977l8.512-6.164v-.126L11.035 10a1.224 1.224 0 0 1 1.782-1.672l6.418 6.827a1.166 1.166 0 0 1 .104 1.423");
}

.zomopvbev {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.1 16.342a1.75 1.75 0 0 1-.59.6l-9.436 6.776a1.225 1.225 0 0 1-1.439-1.977l8.513-6.164v-.127L10.8 9.761a1.224 1.224 0 0 1 1.783-1.672L19 14.916a1.16 1.16 0 0 1 .1 1.426m-3.2 5.07h5.086a1.059 1.059 0 1 1 0 2.118H15.9a1.059 1.059 0 1 1 0-2.118");
}

</style>
