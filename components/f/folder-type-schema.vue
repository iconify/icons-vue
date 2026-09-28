<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><clipPath id="SVGVscIdd9H"><rect class="t8zvnhbwz"/></clipPath></defs><path class="v-16ixbyl"/><g class="kb_esabvd"><g transform="translate(-2.383 -1.048)scale(1.07896)" class="vw18n1bav"><rect clip-path="url(#SVGVscIdd9H)" transform="matrix(-1.05865 0 0 -1 45.673 49.29)" class="bdowt3bqb"/><g class="so6g_ttku"><rect class="d65pfndyv"/><rect class="qq2xxwbwl"/><rect class="ji--c-nna"/></g></g><g transform="translate(-2.383 -1.048)scale(1.07896)"><g class="m5ezkgpve"><rect class="cfutt9vjr"/><rect class="gj4d87bdn"/></g><rect class="s3i_nbwom"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-schema" /></template>
<style>
.bdowt3bqb {
  width: 12.731px;
  height: 6.599px;
  x: 16.635px;
  y: 20.454px;
  fill: none;
  stroke-width: var(--svg-stroke-width--2-37px, 2.37px);
  ry: 0.953px;
}

.cfutt9vjr {
  width: 2px;
  height: 7.75px;
  x: 20.263px;
  y: 17.494px;
  ry: 0.969px;
}

.d65pfndyv {
  width: 3.473px;
  height: 3px;
  x: 13.263px;
  y: 25.026px;
  ry: 0.969px;
}

.gj4d87bdn {
  width: 12px;
  height: 8.875px;
  x: 15.263px;
  y: 11.369px;
  ry: 2.353px;
}

.ji--c-nna {
  width: 3.473px;
  height: 3px;
  x: 25.79px;
  y: 25.006px;
  ry: 0.969px;
}

.kb_esabvd {
  fill: var(--svg-color--fca, #fca);
}

.m5ezkgpve {
  fill: var(--svg-color--ff7a21, #ff7a21);
}

.qq2xxwbwl {
  width: 3.473px;
  height: 3px;
  x: 19.527px;
  y: 25px;
  ry: 0.969px;
}

.s3i_nbwom {
  width: 9.298px;
  height: 2.027px;
  x: 16.614px;
  y: 14.987px;
  ry: 1.014px;
}

.so6g_ttku {
  fill: var(--svg-color--ff7a21, #ff7a21);
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t8zvnhbwz {
  width: 13.224px;
  height: 3.369px;
  x: 16.446px;
  y: 24.001px;
  fill: none;
  stroke: var(--svg-color--ff7a21, #ff7a21);
  stroke-width: var(--svg-stroke-width--0-737px, 0.737px);
  rx: 0px;
  ry: 0.511px;
}

.v-16ixbyl {
  fill: var(--svg-color--953c00, #953c00);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.vw18n1bav {
  stroke: var(--svg-color--ff7a21, #ff7a21);
}

</style>
