<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGVP7Ku7sP"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="fbs9c9b8w"/><path class="bjsppuynf"/><path class="rrrmm119b"/><path class="u6-ix466i"/></g></mask></defs><circle mask="url(#SVGVP7Ku7sP)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:clapperboard-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.bjsppuynf {
  d: path("m12.935 10.698l-2.596-2.503l1.389-1.44l2.595 2.503zm-3.908.855L6.432 9.05L7.82 7.61l2.595 2.504zm7.815-1.711L14.247 7.34l1.388-1.44l2.595 2.504zm-4.01 5.713l2-3l-1.664-1.11l-2 3zm4 0l2-3l-1.664-1.11l-2 3zm-8 0l2-3l-1.664-1.11l-2 3z");
}

.fbs9c9b8w {
  d: path("M3.707 9.08a1 1 0 0 1 .763-1.192L19.123 4.68a1 1 0 0 1 1.19.763l.642 2.93a1 1 0 0 1-.763 1.192L5.54 12.773a1 1 0 0 1-1.19-.763zm2.168.548l.213.977l12.7-2.78l-.214-.977z");
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

.rrrmm119b {
  d: path("M4.5 12a1 1 0 0 1 1-1h15a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1h-15a1 1 0 0 1-1-1zm2 1v7h13v-7z");
}

.u6-ix466i {
  d: path("M21 16H5v-2h16z");
}

</style>
