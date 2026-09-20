<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="l5uql_s8d"/><circle class="eavc5ab_r"/><circle class="oy1f_bcks"/><circle class="a95j84b1h"/><circle class="w6qgb0-3w"/><path class="gsu2fub1f"/><path class="ljhze8bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:camera-with-flash" /></template>
<style>
.a95j84b1h {
  cx: 21px;
  cy: 19px;
  r: 5px;
  fill: var(--svg-color--3b88c3, #3b88c3);
}

.eavc5ab_r {
  cx: 21px;
  cy: 19px;
  r: 10px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.gsu2fub1f {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("m16 9l3-6l-6 2l-4-5l-2 5l-6-1l4 6l-5 4h6l-2 6l6-3l6 5l-1-8l6-1z");
}

.l5uql_s8d {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M0 10s0-4 4-4h28s4 0 4 4v18s0 4-4 4H4s-4 0-4-4z");
}

.ljhze8bsf {
  fill: var(--svg-color--fff, #fff);
  d: path("m10 14l-3 2l1-3l-3-1l3-2l-3-3h4l1-3l2 3l3-1l-2 3l3 3l-3 1l1 4z");
}

.oy1f_bcks {
  cx: 21px;
  cy: 19px;
  r: 8px;
  fill: var(--svg-color--31373d, #31373d);
}

.w6qgb0-3w {
  cx: 32.5px;
  cy: 9.5px;
  r: 1.5px;
  fill: var(--svg-color--fff, #fff);
}

</style>
