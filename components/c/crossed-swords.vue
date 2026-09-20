<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="as86nzbsi"/><g class="a2yy6zb5x"><path class="c-eteue1e"/><circle transform="rotate(-45.001 105.81 72.054)" class="pqxwspbsg"/><circle transform="rotate(-45.001 72.079 105.784)" class="i7kmbsbxb"/></g><path class="gg--5co6l"/><path class="zqvtgyrig"/><path class="s8-lqlb1q"/><path class="fl9lq2bwd"/><path class="f6jo65buz"/><path class="fjkqxtrrt"/><g class="a2yy6zb5x"><path class="ducprpbih"/><circle transform="rotate(-45.001 18.196 75.849)" class="v4fmg933t"/><circle transform="rotate(-45.001 52.82 110.474)" class="y5f9ogbgb"/></g><path class="zjyetsb_m"/><path class="vmgh9wb5l"/><path class="p6b98bbsv"/><path class="xv9hf-kzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:crossed-swords" /></template>
<style>
.a2yy6zb5x {
  fill: var(--svg-color--78a3ad, #78a3ad);
}

.as86nzbsi {
  fill: var(--svg-color--855c52, #855c52);
  d: path("m120.51 126.91l6.43-6.43c.96-.96.96-2.51 0-3.47L94.45 84.53a2.45 2.45 0 0 0-3.47 0l-6.43 6.43a2.45 2.45 0 0 0 0 3.47l32.49 32.49c.96.95 2.51.95 3.47-.01");
}

.c-eteue1e {
  d: path("m72.09 109.36l37.3-37.3c.77-.77.77-2.01 0-2.78l-1.11-1.11c-.77-.77-2.01-.77-2.78 0l-37.3 37.3c-.77.77-.77 2.01 0 2.78l1.11 1.11c.76.77 2.01.77 2.78 0");
}

.ducprpbih {
  d: path("m51.24 114.04l-37.3-37.3c-.77-.77-.77-2.01 0-2.78l1.11-1.11c.77-.77 3.21-2.29 3.98-1.52l37.3 37.3c.77.77-.42 3.53-1.19 4.3l-1.11 1.11c-.78.77-2.03.77-2.79 0");
}

.f6jo65buz {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("M10.89.96L0-.03l86.84 86.84l4.95-4.94z");
}

.fjkqxtrrt {
  fill: var(--svg-color--855c52, #855c52);
  d: path("m7.49 126.97l-6.43-6.43a2.45 2.45 0 0 1 0-3.47l27.81-27.86a2.45 2.45 0 0 1 3.47 0l6.43 6.43c.96.96.96 2.51 0 3.47l-27.81 27.86c-.96.96-2.51.96-3.47 0");
}

.fl9lq2bwd {
  fill: var(--svg-color--64878e, #64878e);
  d: path("m0-.03l.99 10.89l80.9 80.9l4.95-4.95z");
}

.gg--5co6l {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("m85.789 95.66l9.899-9.9l2.659 2.659l-9.9 9.899z");
}

.i7kmbsbxb {
  cx: 72.08px;
  cy: 105.78px;
  r: 4.49px;
}

.p6b98bbsv {
  fill: var(--svg-color--64878e, #64878e);
  d: path("m128 .03l-.99 10.88l-85.58 85.53l-4.95-4.94z");
}

.pqxwspbsg {
  cx: 105.81px;
  cy: 72.05px;
  r: 4.49px;
}

.s8-lqlb1q {
  fill: var(--svg-color--2b94c5, #2b94c5);
  d: path("m0-.03l10.89.99l80.9 80.91l-4.95 4.94z");
}

.v4fmg933t {
  cx: 18.2px;
  cy: 75.85px;
  r: 6.16px;
}

.vmgh9wb5l {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("m1.12 123.12l3.79 3.79c1.69 1.69 4.67 1.44 6.66-.55l-9.9-9.9c-1.99 1.99-2.24 4.97-.55 6.66M128 .03l-10.89.99l-85.58 85.53l4.95 4.95z");
}

.xv9hf-kzl {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("m64.02 73.87l9.89-9.89l4.36 4.32l-9.69 10.12z");
}

.y5f9ogbgb {
  cx: 52.82px;
  cy: 110.47px;
  r: 6.16px;
}

.zjyetsb_m {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("m24.978 93.098l2.659-2.66l9.9 9.9l-2.66 2.659z");
}

.zqvtgyrig {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("m126.88 123.06l-3.79 3.79c-1.69 1.69-4.67 1.44-6.66-.55l9.9-9.9c1.99 2 2.24 4.98.55 6.66");
}

</style>
