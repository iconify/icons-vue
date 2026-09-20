<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGGgKOWdDe" x1="433.5" x2="337.15" y1="231.36" y2="93.87" gradientTransform="rotate(47.41 127.68 243.31)" gradientUnits="userSpaceOnUse"><stop offset="0" class="h3jeyzb7e"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGRGjgpOMv" x1="380" x2="312.12" y1="592.36" y2="298.62" gradientUnits="userSpaceOnUse"><stop offset="0" class="qnqtogd6c"/><stop offset="1" class="vc--wpv5i"/></linearGradient></defs><g class="jxqi2jbpi"><path fill="url(#SVGGgKOWdDe)" transform="translate(-21.86 -30.12)scale(.09964)" class="hq-gmqyli"/><path fill="url(#SVGRGjgpOMv)" transform="translate(-21.86 -30.12)scale(.09964)" class="jffiycjvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-direnv" /></template>
<style>
.h3jeyzb7e {
  stop-color: var(--svg-color--3ab809, #3ab809);
}

.hq-gmqyli {
  stroke-opacity: 0.21;
  d: path("M319.91 355c-14.72 13.53-30.9 32.87-6.06 59.9c24.83 27.03 45.47 12.54 60.2-.99s28.71-55.04 28.15-80.2c-25.03-2.7-67.56 7.76-82.29 21.29z");
}

.jffiycjvq {
  fill-rule: evenodd;
  stroke-opacity: 0.26;
  d: path("M250 392.38v20h-10v180h280v-180H330v-20z");
}

.jxqi2jbpi {
  stroke: var(--svg-color--000, #000);
}

.qnqtogd6c {
  stop-color: var(--svg-color--0aafc7, #0aafc7);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
