<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="g9rvrub_x"/><path class="h82gk3uiy"/><ellipse class="n8uhd2kbj"/><ellipse class="qoujeeb6i"/><path class="kqhxncb0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-smile-line-duotone" /></template>
<style>
.g9rvrub_x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 2.2627V5.0003C13 7.35732 13 8.53583 13.7322 9.26806C14.4645 10.0003 15.643 10.0003 18 10.0003H21.58");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.h82gk3uiy {
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 17.5C10.8167 18.7111 13.1833 18.7111 15 17.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.kqhxncb0k {
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.17139 3.17157C4.34296 2 6.23851 2 10.0296 2C11.5546 2 12.3173 2.00011 13.0093 2.26562C13.7012 2.53114 14.2651 3.03857 15.3929 4.05365L19.3516 7.61621C20.6558 8.78998 21.3078 9.3774 21.6538 10.1543C21.9998 10.9312 22 11.8079 22 13.5625V14C22 17.7712 22 19.6566 20.8284 20.8281C19.6569 21.9997 17.7712 22 14 22L9.9969 21.9997C6.22761 21.9997 4.34284 21.9997 3.17157 20.8284C2 19.6569 2 17.7712 2 14V9.9982C2 6.22817 2 4.34296 3.17139 3.17157Z");
}

.n8uhd2kbj {
  cx: 7px;
  cy: 14.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 0.5px;
  ry: 1px;
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.qoujeeb6i {
  cx: 17px;
  cy: 14.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 0.5px;
  ry: 1px;
}

</style>
