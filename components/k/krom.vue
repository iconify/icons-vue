<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG76mRtdBt)" class="q9rrdcbep"/><defs><linearGradient id="SVG76mRtdBt" x1="3" x2="21" y1="11.999" y2="11.999" gradientUnits="userSpaceOnUse"><stop class="y1nt4abzr"/><stop offset=".23" class="czr822ilr"/><stop offset=".52" class="q104xjbgq"/><stop offset=".74" class="imuiplmqx"/><stop offset=".9" class="ses-2u7_r"/><stop offset="1" class="e5gwm5bdm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:krom" /></template>
<style>
.czr822ilr {
  stop-color: var(--svg-color--aac5f9, #aac5f9);
}

.e5gwm5bdm {
  stop-color: var(--svg-color--aea0f4, #aea0f4);
}

.ft5dv1b6b {
  fill: none;
}

.imuiplmqx {
  stop-color: var(--svg-color--b6b5f7, #b6b5f7);
}

.q104xjbgq {
  stop-color: var(--svg-color--a5bcf8, #a5bcf8);
}

.q9rrdcbep {
  d: path("m19.375 19.457l-7.339-6.246L4.5 19.583c-.582.492-1.5.096-1.5-.654V5.069c0-.75.918-1.14 1.5-.654l7.536 6.402l7.405-6.318a.96.96 0 0 1 1.32.072a.88.88 0 0 1-.078 1.278l-7.225 6.132l7.17 6.12a.88.88 0 0 1 .09 1.272a.973.973 0 0 1-1.343.084M4.8 6.983v9.978l5.814-4.956z");
}

.ses-2u7_r {
  stop-color: var(--svg-color--ebb0f2, #ebb0f2);
}

.y1nt4abzr {
  stop-color: var(--svg-color--9eebfd, #9eebfd);
}

</style>
