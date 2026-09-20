<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGPHL7DeMo" x1="4.416" x2="13.909" y1="-1909.341" y2="-1892.9" gradientTransform="translate(0 1917.121)" gradientUnits="userSpaceOnUse"><stop offset="0" class="b7bjkwrag"/><stop offset=".5" class="a_0xnlbhw"/><stop offset="1" class="r1mwh5kgg"/></linearGradient></defs><path class="yq3ni3bke"/><path class="k444ogrpp"/><path class="t5i-p9bqm"/><ellipse class="y7izzq11j"/><path class="p_sz6fbyr"/><path class="k7qdtbwdq"/><path class="v0w4uab3n"/><path class="ysarbzp5x"/><path fill="url(#SVGPHL7DeMo)" class="iqv6avejg"/><path class="d1fsh5_fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-access" /></template>
<style>
.a_0xnlbhw {
  stop-color: var(--svg-color--b12334, #b12334);
}

.b7bjkwrag {
  stop-color: var(--svg-color--b72c3f, #b72c3f);
}

.d1fsh5_fh {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.305 12.027h1.758l2.825 7.945h-1.66l-.623-1.895H7.7l-.611 1.895H5.437Zm1.926 4.826l-.9-2.875a4 4 0 0 1-.165-.649H9.13a3.7 3.7 0 0 1-.162.671l-.912 2.859Z");
}

.iqv6avejg {
  d: path("M3.194 8.667h11.938a1.21 1.21 0 0 1 1.194 1.222v12.222a1.21 1.21 0 0 1-1.194 1.222H3.194A1.21 1.21 0 0 1 2 22.111V9.889a1.21 1.21 0 0 1 1.194-1.222");
}

.k444ogrpp {
  fill: var(--svg-color--af2031, #af2031);
  d: path("M8.512 12.667V20c0 1.841 4.81 3.333 10.744 3.333S30 21.841 30 20v-7.333Z");
}

.k7qdtbwdq {
  d: path("M15.783 8.667H8.512v16.666h7.271a1.21 1.21 0 0 0 1.194-1.222V9.889a1.21 1.21 0 0 0-1.194-1.222");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p_sz6fbyr {
  d: path("M16.434 8H8.512v16.667h7.922a1.21 1.21 0 0 0 1.194-1.222V9.222A1.21 1.21 0 0 0 16.434 8");
  opacity: var(--svg-opacity--0-1, 0.1);
}

.r1mwh5kgg {
  stop-color: var(--svg-color--9d1623, #9d1623);
}

.t5i-p9bqm {
  fill: var(--svg-color--c94f60, #c94f60);
  d: path("M8.512 5.333v7.334c0 1.84 4.81 3.333 10.744 3.333S30 14.507 30 12.667V5.333Z");
}

.v0w4uab3n {
  d: path("M15.783 8.667H8.512V24h7.271a1.21 1.21 0 0 0 1.194-1.222V9.889a1.21 1.21 0 0 0-1.194-1.222");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y7izzq11j {
  cx: 19.256px;
  cy: 5.333px;
  fill: var(--svg-color--e08095, #e08095);
  rx: 10.744px;
  ry: 3.333px;
}

.yq3ni3bke {
  fill: var(--svg-color--881421, #881421);
  d: path("M8.512 20v6.667c0 1.84 4.81 3.333 10.744 3.333S30 28.507 30 26.667V20Z");
}

.ysarbzp5x {
  d: path("M15.132 8.667h-6.62V24h6.62a1.213 1.213 0 0 0 1.194-1.222V9.889a1.213 1.213 0 0 0-1.194-1.222");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
