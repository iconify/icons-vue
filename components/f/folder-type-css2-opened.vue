<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xf6tsacjh"/><path class="u_1vr7b9g"/><path class="vrygz-bqg"/><path class="eypj8zbik"/><path class="lt3yyz0_v"/><path class="gvt1zx_cb"/><path class="i0tzjacag"/><path class="d9_lgqblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-css2-opened" /></template>
<style>
.d9_lgqblf {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("M21.758 13.701v2.318h-5.599l-.047-.521l-.105-1.175l-.056-.622zm-.008 4.692v2.319h-2.549l-.046-.521l-.106-1.176l-.055-.622z");
}

.eypj8zbik {
  fill: var(--svg-color--33a9dc, #33a9dc);
  d: path("m21.75 29.393l6.127-1.699l1.442-16.149H21.75z");
}

.gvt1zx_cb {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("m21.764 24.413l-.01.003l-2.582-.697l-.165-1.849H16.68l.325 3.64l4.748 1.318l.011-.003z");
}

.i0tzjacag {
  fill: var(--svg-color--fff, #fff);
  d: path("m24.62 20.613l-.279 3.105l-2.585.697v2.412l4.752-1.317l.035-.392l.403-4.505z");
}

.lt3yyz0_v {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.75 18.393h3.068l.211-2.374H21.75v-2.318h5.813l-.056.622l-.57 6.388H21.75z");
}

.u_1vr7b9g {
  fill: var(--svg-color--7bb6db, #7bb6db);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.vrygz-bqg {
  fill: var(--svg-color--1572b6, #1572b6);
  d: path("M14.177 28.901L12.492 10h18.516l-1.686 18.898L21.739 31z");
}

.xf6tsacjh {
  fill: var(--svg-color--7bb6db, #7bb6db);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

</style>
