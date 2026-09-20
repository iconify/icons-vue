<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="x4stwgbgx"/><path fill="url(#SVGOtC5nbMH)" class="xzzn91b1l"/><path fill="url(#SVGPUXKCHdP)" class="gqfsuzbrx"/><path class="w1yeceqod"/><defs><linearGradient id="SVGOtC5nbMH" x1="19.803" x2="7.994" y1="4.404" y2="13.022" gradientUnits="userSpaceOnUse"><stop class="rrjbtmw-q"/><stop offset="1" class="j7an9vb0d"/></linearGradient><linearGradient id="SVGPUXKCHdP" x1="15.921" x2="2.637" y1="11.784" y2="18.975" gradientUnits="userSpaceOnUse"><stop class="e4-7kfdzw"/><stop offset="1" class="tggr57b1v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:l2" /></template>
<style>
.e4-7kfdzw {
  stop-color: var(--svg-color--935e26, #935e26);
}

.ft5dv1b6b {
  fill: none;
}

.gqfsuzbrx {
  d: path("m10.877 8.062l-5.23 9.233h10.508z");
}

.j7an9vb0d {
  stop-color: var(--svg-color--e0a662, #e0a662);
}

.rrjbtmw-q {
  stop-color: var(--svg-color--915512, #915512);
}

.tggr57b1v {
  stop-color: var(--svg-color--f1bd84, #f1bd84);
}

.w1yeceqod {
  fill: var(--svg-color--ffcd05, #ffcd05);
  d: path("m9.745 10.063l3.336 5.876l1.148-2.012l-3.351-5.865z");
}

.x4stwgbgx {
  fill: var(--svg-color--fc8800, #fc8800);
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m0-.53a8.47 8.47 0 1 0 0-16.94a8.47 8.47 0 0 0 0 16.94");
}

.xzzn91b1l {
  d: path("M13.08 15.939L7.844 6.706h10.509z");
}

</style>
