<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="a44teab8o"/><path class="cm3_e8blk"/><g class="mrjy-p0fq"><ellipse class="i77kqvbab"/><ellipse class="yi6dfvbpi"/></g><path class="e1z0h-bwi"/><path class="np9pd3o_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:grinning-face-with-big-eyes" /></template>
<style>
.a44teab8o {
  fill: var(--svg-color--fbbf67, #fbbf67);
  d: path("M63.58 32.04c0 17.522-14.2 31.728-31.726 31.728S.128 49.562.128 32.04C.128 14.514 14.328.308 31.854.308S63.58 14.514 63.58 32.04");
}

.cm3_e8blk {
  fill: var(--svg-color--fff, #fff);
  d: path("M27.28 20.789c0 7.417-2.887 13.419-6.447 13.419c-3.564 0-6.451-6-6.451-13.419c0-7.415 2.886-13.418 6.451-13.418c3.56 0 6.447 6 6.447 13.418m21.81 0c0 7.417-2.883 13.419-6.447 13.419c-3.56 0-6.448-6-6.448-13.419c0-7.415 2.889-13.418 6.448-13.418c3.564 0 6.447 6 6.447 13.418");
}

.e1z0h-bwi {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M51.12 40.34c0 11.02-8.941 19.963-19.966 19.963c-11.02 0-19.959-8.942-19.959-19.963");
}

.i77kqvbab {
  cx: 20.827px;
  cy: 21.416px;
  rx: 4.174px;
  ry: 5.06px;
}

.mrjy-p0fq {
  fill: var(--svg-color--25333a, #25333a);
}

.np9pd3o_l {
  fill: var(--svg-color--fff, #fff);
  d: path("M47.695 42.34c0 4.4-7.56 7.975-16.879 7.975c-9.312 0-16.873-3.574-16.873-7.975");
}

.yi6dfvbpi {
  cx: 42.649px;
  cy: 21.416px;
  rx: 4.172px;
  ry: 5.06px;
}

</style>
