<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="edm2av0vf"/><path class="zsa2kdbdw"/><path class="d76hi_bnp"/><path class="iumob5e9e"/><path class="z25lovqsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-smile-linear" /></template>
<style>
.d76hi_bnp {
  d: path("M17.5 14.5C17.5 15.0523 17.2761 15.5 17 15.5C16.7239 15.5 16.5 15.0523 16.5 14.5C16.5 13.9477 16.7239 13.5 17 13.5C17.2761 13.5 17.5 13.9477 17.5 14.5Z");
}

.edm2av0vf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 17.5C10.8167 18.7111 13.1833 18.7111 15 17.5");
}

.iumob5e9e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 2.2627V5.0003C13 7.35732 13 8.53583 13.7322 9.26806C14.4645 10.0003 15.643 10.0003 18 10.0003H21.58");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z25lovqsv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.17139 3.17157C4.34296 2 6.23851 2 10.0296 2C11.5546 2 12.3173 2.00011 13.0093 2.26562C13.7012 2.53114 14.2651 3.03857 15.3929 4.05365L19.3516 7.61621C20.6558 8.78998 21.3078 9.3774 21.6538 10.1543C21.9998 10.9312 22 11.8079 22 13.5625V14C22 17.7712 22 19.6566 20.8284 20.8281C19.6569 21.9997 17.7712 22 14 22L9.9969 21.9997C6.22761 21.9997 4.34284 21.9997 3.17157 20.8284C2 19.6569 2 17.7712 2 14V9.9982C2 6.22817 2 4.34296 3.17139 3.17157Z");
}

.zsa2kdbdw {
  d: path("M7.5 14.5C7.5 15.0523 7.27614 15.5 7 15.5C6.72386 15.5 6.5 15.0523 6.5 14.5C6.5 13.9477 6.72386 13.5 7 13.5C7.27614 13.5 7.5 13.9477 7.5 14.5Z");
}

</style>
