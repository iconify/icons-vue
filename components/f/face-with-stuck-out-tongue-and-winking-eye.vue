<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="j9snujhxu"/><path class="f41ko9byd"/><path class="d9c2bub6x"/><path class="abscvybza"/><path class="l3fy1n1gj"/><path class="zq66-bmrp"/><ellipse class="a5wjyzbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:face-with-stuck-out-tongue-and-winking-eye" /></template>
<style>
.a5wjyzbnq {
  cx: 42.977px;
  cy: 25.09px;
  fill: var(--svg-color--25333a, #25333a);
  rx: 4.132px;
  ry: 5.01px;
}

.abscvybza {
  fill: var(--svg-color--f45ba1, #f45ba1);
  d: path("M42.26 56.23c0 4.03-4.55 7.303-10.163 7.303c-5.61 0-10.16-3.27-10.16-7.303l2.19-8.422c0-4.03 2.359-5.313 7.97-5.313c5.613 0 7.972 1.282 7.972 5.313z");
}

.d9c2bub6x {
  fill: var(--svg-color--fff, #fff);
  d: path("M53.36 25.09c0 6.274-4.646 11.349-10.385 11.349S32.586 31.364 32.586 25.09c0-6.267 4.65-11.348 10.389-11.348S53.36 18.824 53.36 25.09");
}

.f41ko9byd {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M51.685 39.15c0 10.911-8.853 19.766-19.768 19.766c-10.907 0-19.762-8.854-19.762-19.766");
}

.j9snujhxu {
  cx: 31.76px;
  cy: 31.816px;
  r: 31.713px;
  fill: var(--svg-color--fbbf67, #fbbf67);
}

.l3fy1n1gj {
  fill: var(--svg-color--fff, #fff);
  d: path("M48.3 41.13c0 4.357-7.484 7.896-16.712 7.896c-9.219 0-16.706-3.539-16.706-7.896");
}

.zq66-bmrp {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M28.14 29.17c-.233 0-4.493-1.548-8.798-1.548c-3.843 0-7.72 1.548-8.798 1.548c-.935 0-1.285-1.024-.718-1.637a12.84 12.84 0 0 1 19.03 0c.562.612.213 1.637-.718 1.637");
}

</style>
