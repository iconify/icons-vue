<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rarcsqb4a"/><path class="l5uql_s8d"/><circle class="eavc5ab_r"/><circle class="oy1f_bcks"/><circle class="a95j84b1h"/><circle class="w6qgb0-3w"/><path class="cvd5ezbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:camera" /></template>
<style>
.a95j84b1h {
  cx: 21px;
  cy: 19px;
  r: 5px;
  fill: var(--svg-color--3b88c3, #3b88c3);
}

.cvd5ezbtu {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M12 9.5a1.5 1.5 0 0 1-1.5 1.5h-5a1.5 1.5 0 1 1 0-3h5A1.5 1.5 0 0 1 12 9.5");
}

.eavc5ab_r {
  cx: 21px;
  cy: 19px;
  r: 10px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.l5uql_s8d {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M0 10s0-4 4-4h28s4 0 4 4v18s0 4-4 4H4s-4 0-4-4z");
}

.oy1f_bcks {
  cx: 21px;
  cy: 19px;
  r: 8px;
  fill: var(--svg-color--31373d, #31373d);
}

.rarcsqb4a {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M4 5s0-1 1-1h6s1 0 1 1v2H4z");
}

.w6qgb0-3w {
  cx: 32.5px;
  cy: 9.5px;
  r: 1.5px;
  fill: var(--svg-color--fff, #fff);
}

</style>
