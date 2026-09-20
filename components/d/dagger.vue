<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="le3yilfsh"/><path class="neu163p_v"/><path class="k3rer0yhk"/><circle transform="rotate(-45.001 119.055 9.088)" class="m5kqlx-_b"/><path class="r3rtqhb-j"/><path class="rrsg9ib6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:dagger" /></template>
<style>
.k3rer0yhk {
  fill: var(--svg-color--64878e, #64878e);
  d: path("M.26 127.55c3.11-.01 31.84-22.58 33.39-23.92l55.1-48.39a4.397 4.397 0 0 0 .24-6.43L84 43.82z");
}

.le3yilfsh {
  fill: var(--svg-color--875a3b, #875a3b);
  d: path("m85.38 31.88l11.6 11.6l21.89-27.65l-6.92-6.92z");
}

.m5kqlx-_b {
  cx: 119.05px;
  cy: 9.09px;
  r: 8.33px;
  fill: var(--svg-color--875a3b, #875a3b);
}

.neu163p_v {
  fill: var(--svg-color--78a3ad, #78a3ad);
  stroke: var(--svg-color--78a3ad, #78a3ad);
  stroke-miterlimit: 10;
  d: path("m88.99 48.82l-10.01-10a4.363 4.363 0 0 0-6.4.24l-48.4 55.11C22.79 95.76-1.46 126 .04 127.49c1.5 1.5 32.01-22.47 33.61-23.86l55.11-48.4a4.38 4.38 0 0 0 .23-6.41z");
}

.r3rtqhb-j {
  fill: var(--svg-color--64878e, #64878e);
  d: path("m83.95 33.29l-4.97 5.53l10.37 10.41l5.68-5.69z");
}

.rrsg9ib6k {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("M106.42 48.34c-2.06-2.06-8.64-8.72-12.09-12.22l.01-.01s-.41-.41-1.1-1.08c-.68-.69-1.08-1.1-1.08-1.1l-.01.01C88.65 30.49 82 23.91 79.93 21.85c-2.84-2.84-8.26-3.13-11.14-.23c-1.1 1.1-1.55 2.84-1.29 4.32c.4 2.28 2.49 4 4.48 4.32c2.36.38 2.89-.67 5.23-.65c1.83.01 3.08 1.33 3.08 1.33l2.64 2.64l4.79 4.79l2.18 2.18l4.79 4.79l2.64 2.64s1.31 1.25 1.33 3.08c.02 2.34-1.03 2.87-.65 5.23c.32 1.99 2.04 4.08 4.32 4.48c1.49.26 3.22-.19 4.32-1.29c2.9-2.89 2.61-8.3-.23-11.14");
}

</style>
