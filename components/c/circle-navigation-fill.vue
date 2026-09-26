<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lej-24q4i"/><path class="h6hs587dj"/><path class="yyw8rgbsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-navigation-fill" /></template>
<style>
.h6hs587dj {
  fill: currentColor;
  d: path("M8.1312 19.3647L11.1113 13.5654C11.4986 12.8115 12.5014 12.8115 12.8887 13.5654L15.8688 19.3647C16.3118 20.2268 15.5616 21.2346 14.6879 20.9513L12.2921 20.1742C12.1016 20.1124 11.8984 20.1124 11.7079 20.1742L9.3121 20.9513C8.4384 21.2346 7.6882 20.2268 8.1312 19.3647Z");
  stroke: none;
}

.lej-24q4i {
  d: path("M20 19C21.2982 17.269 22 15.1637 22 13C22 7.4772 17.5229 3 12 3C6.4772 3 2 7.4772 2 13C2 15.1637 2.7018 17.269 4 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yyw8rgbsu {
  d: path("M8.1312 19.3647L11.1113 13.5654C11.4986 12.8115 12.5014 12.8115 12.8887 13.5654L15.8688 19.3647C16.3118 20.2268 15.5616 21.2346 14.6879 20.9513L12.2921 20.1742C12.1016 20.1124 11.8984 20.1124 11.7079 20.1742L9.3121 20.9513C8.4384 21.2346 7.6882 20.2268 8.1312 19.3647Z");
}

</style>
