<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y3wbdac5q"/><path class="qvdfr62dc"/><path class="in9q6_f2a"/><path class="ti4rjlbxd"/><path class="s5g8tm5gz"/><path class="f-x4b7csg"/><path class="ytclnmd3h"/><path class="tf2f-x8gf"/><path class="trutp-bil"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bacteria-broken" /></template>
<style>
.f-x4b7csg {
  d: path("M13.4209 17.772L14.9995 19");
}

.in9q6_f2a {
  d: path("M14.4648 7.17138C14.4648 7.17138 15.7077 7 16.5862 7.87849C17.4647 8.75698 17.2933 9.99981 17.2933 9.99981");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.qvdfr62dc {
  d: path("M4.5 11.5L4.91406 10.5");
}

.s5g8tm5gz {
  d: path("M18.9996 13.1362C18.9996 13.1362 17.8376 13.6092 17.516 14.8093C17.1945 16.0093 17.9643 16.9999 17.9643 16.9999");
}

.tf2f-x8gf {
  d: path("M12 5H10");
}

.ti4rjlbxd {
  d: path("M9.00013 9.29297C9.00013 9.29297 7.7573 9.46435 6.87881 8.58586C6.00032 7.70737 6.1717 6.46454 6.1717 6.46454");
}

.trutp-bil {
  d: path("M12.5 9.5L11.5 8.5");
}

.y3wbdac5q {
  d: path("M6 15C6 13.3431 7.34315 12 9 12C10.6569 12 12 13.3431 12 15C12 16.6569 10.6569 18 9 18C7.34315 18 6 16.6569 6 15Z");
}

.ytclnmd3h {
  d: path("M14.5 14V12");
}

</style>
