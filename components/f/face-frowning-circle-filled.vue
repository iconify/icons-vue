<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG2JYKeePY"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="ds5ly2jxw"/><path class="h5q-b7bfk"/><path clip-rule="evenodd" class="rk73ncc5t"/></g></mask></defs><circle mask="url(#SVG2JYKeePY)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:face-frowning-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ds5ly2jxw {
  fill-rule: evenodd;
  d: path("M13 20.5a7.5 7.5 0 1 0 0-15a7.5 7.5 0 0 0 0 15m0 2a9.5 9.5 0 1 0 0-19a9.5 9.5 0 0 0 0 19");
}

.ft5dv1b6b {
  fill: none;
}

.h5q-b7bfk {
  d: path("M11.5 10.25a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m5.5 0a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.rk73ncc5t {
  fill-rule: evenodd;
  d: path("M15.221 17.627A1 1 0 0 0 16.8 16.4l-.8.6l.8-.601l-.002-.001l-.001-.003l-.004-.005l-.01-.011l-.08-.095a3 3 0 0 0-.191-.188a3.6 3.6 0 0 0-.698-.478C15.192 15.286 14.28 15 13 15s-2.192.286-2.814.618a3.6 3.6 0 0 0-.698.478a3 3 0 0 0-.272.283l-.009.011l-.003.005l-.002.003H9.2c0 .001-.001.002.799.602l-.8-.6a1 1 0 0 0 1.579 1.227l.038-.036c.05-.044.15-.123.31-.209c.315-.168.902-.382 1.873-.382c.97 0 1.558.214 1.873.382a1.6 1.6 0 0 1 .348.245");
}

</style>
