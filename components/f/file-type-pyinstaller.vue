<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGUhpSXb5U" x1="4.843" x2="18.102" y1="4.735" y2="18.022" gradientUnits="userSpaceOnUse"><stop offset="0" class="aw-t_bg-j"/><stop offset="1" class="z8bgr0bko"/></linearGradient><linearGradient id="SVGdab7ddZI" x1="12.586" x2="27.736" y1="13.547" y2="26.833" gradientUnits="userSpaceOnUse"><stop offset="0" class="h2odc0bvt"/><stop offset="1" class="jxpbwgawm"/></linearGradient></defs><path fill="url(#SVGUhpSXb5U)" class="trgml5g-e"/><path fill="url(#SVGdab7ddZI)" class="sq9qnccum"/><rect class="qs5fbb51b"/><rect class="rct7z9bam"/><rect class="mnq00996e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-pyinstaller" /></template>
<style>
.aw-t_bg-j {
  stop-color: var(--svg-color--387eb8, #387eb8);
}

.h2odc0bvt {
  stop-color: var(--svg-color--ffe052, #ffe052);
}

.jxpbwgawm {
  stop-color: var(--svg-color--ffc331, #ffc331);
}

.mnq00996e {
  width: 9px;
  height: 5px;
  x: 17px;
  y: 24px;
  fill: var(--svg-color--6ea0c2, #6ea0c2);
  ry: 0.313px;
}

.qs5fbb51b {
  width: 17px;
  height: 16.45px;
  x: 13px;
  y: 12.55px;
  fill: var(--svg-color--214b6b, #214b6b);
  ry: 1.125px;
}

.rct7z9bam {
  width: 13px;
  height: 8px;
  x: 15px;
  y: 13px;
  fill: var(--svg-color--9ac7ea, #9ac7ea);
  ry: 0.5px;
}

.sq9qnccum {
  d: path("M16.043 29.998c7.1 0 6.651-3.08 6.651-3.08v-3.18h-6.751v-1h9.47s4.545.508 4.545-6.655s-4.013-6.912-4.013-6.912h-2.347v3.317s.13 4.013-3.9 4.013h-6.765s-3.775-.057-3.775 3.655v6.132S8.586 30 16 30h.04zm3.732-2.147c-1.081.027-1.656-1.266-.91-2.05s2.066-.275 2.093.806v.03c0 .67-.544 1.214-1.214 1.214z");
}

.trgml5g-e {
  d: path("M15.963 2.012c-7.1 0-6.651 3.07-6.651 3.07v3.19h6.752v1H6.623s-4.545-.56-4.545 6.645s4.013 6.912 4.013 6.912h2.317v-3.361s-.13-4.013 3.9-4.013h6.762s3.772.06 3.772-3.652V5.712S23.414 2 16 2zm-3.732 2.137a1.214 1.214 0 1 1-1.183 1.244v-.02a1.214 1.214 0 0 1 1.214-1.214z");
}

.z8bgr0bko {
  stop-color: var(--svg-color--366994, #366994);
}

</style>
