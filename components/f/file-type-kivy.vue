<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGPOtEoeKo" x1="14.989" x2="15.124" y1="17.164" y2="17.091" gradientTransform="matrix(1 0 0 -1 0 34)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sf3u6-8dg"/><stop offset=".085" class="u08pfvblg"/><stop offset=".224" class="u8kzt5bkl"/><stop offset=".398" class="u-lj9c7jf"/><stop offset=".603" class="jdti_rsoy"/><stop offset=".83" class="p1r9pcv5x"/><stop offset="1" class="stui2mbih"/></linearGradient></defs><circle class="mu3cuhb6g"/><path class="w88gdgsmk"/><path class="y-596_kuy"/><path fill="url(#SVGPOtEoeKo)" class="uf2qzbc-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-kivy" /></template>
<style>
.jdti_rsoy {
  stop-color: var(--svg-color--gray, gray);
  stop-opacity: 0.012;
}

.mu3cuhb6g {
  cx: 16px;
  cy: 16px;
  r: 14px;
  fill: var(--svg-color--3f4142, #3f4142);
}

.p1r9pcv5x {
  stop-color: var(--svg-color--c6c6c6, #c6c6c6);
  stop-opacity: 0.005;
}

.sf3u6-8dg {
  stop-opacity: 0.03;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.u-lj9c7jf {
  stop-color: var(--svg-color--494949, #494949);
  stop-opacity: 0.018;
}

.u08pfvblg {
  stop-color: var(--svg-color--090909, #090909);
  stop-opacity: 0.027;
}

.u8kzt5bkl {
  stop-color: var(--svg-color--212121, #212121);
  stop-opacity: 0.023;
}

.uf2qzbc-y {
  d: path("m16.488 13.975l.115.115l-3.007 5.665l-.115-.115z");
}

.w88gdgsmk {
  fill: var(--svg-color--ebeded, #ebeded);
  d: path("m26.469 12.631l-8.992 1.019l4.146 4.14l4.948-4.942c.145-.148.097-.241-.102-.217m-6.196 5.129l-3.785-3.785l-3.007 5.665l2.441 2.441a1 1 0 0 0 .705.289a1 1 0 0 0 .705-.289l2.935-2.917a.98.98 0 0 0 .289-.7a.96.96 0 0 0-.283-.704");
}

.y-596_kuy {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M12.1 9.588v7.407a3.62 3.62 0 0 0 .892 2.158l.488.488l3.007-5.665Zm-4.194 9.486l3.266 3.266v-7.75l-3.266 3.266a.87.87 0 0 0 0 1.218m2.471-6.208L7.111 9.6v7.744l3.266-3.266a.86.86 0 0 0 0-1.212");
}

</style>
