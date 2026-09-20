<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG7NrgLyQc"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="y7o1k1bsn"/><path class="r1-p38bpp"/></g></mask></defs><circle mask="url(#SVG7NrgLyQc)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:key-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.r1-p38bpp {
  d: path("M13 8.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m0-2a.5.5 0 1 1 0 1a.5.5 0 0 1 0-1");
}

.y7o1k1bsn {
  d: path("M15.718 15.307A1 1 0 0 0 16 14.61V12a5 5 0 1 0-6 0v8a3 3 0 1 0 6 0a1 1 0 0 0-.365-.772l-.226-.186l.088-.05a1 1 0 0 0 .503-.868v-.775a1 1 0 0 0-.292-.706l-.65-.653zm-1.75-3.558Q14 11.872 14 12v2.206l-1.063 1.098a1 1 0 0 0 .01 1.402l.915.917l-.703.402a1 1 0 0 0-.14 1.64l.897.738A1 1 0 0 1 12 20v-8q0-.13.031-.25a1 1 0 0 0-.483-1.124a3 3 0 1 1 2.904 0a1 1 0 0 0-.483 1.124");
}

</style>
