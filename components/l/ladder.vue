<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="p04_5_bgk"/><path class="ni5-azbtp"/><path class="eavznbclk"/><path class="t1zb_55ua"/><path class="ox8xm_bso"/><path class="tj1t-lp-v"/><path class="yhvpirhtx"/><path class="kginkqwtr"/><path class="u9w1-9b5y"/><path class="qb2f2gd_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:ladder" /></template>
<style>
.eavznbclk {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M26 13H10a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h16a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1");
}

.kginkqwtr {
  fill: var(--svg-color--662113, #662113);
  d: path("M10 35c.55 0 1-.45 1-1V2c0-.55-.45-1-1-1s-1 .45-1 1v32c0 .55.45 1 1 1");
}

.ni5-azbtp {
  fill: var(--svg-color--662113, #662113);
  d: path("M10 22.5h16V24H10z");
}

.ox8xm_bso {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M26 5H10a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h16a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1m0 24H10a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h16a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1");
}

.p04_5_bgk {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M26 21H10a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h16a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1");
}

.qb2f2gd_j {
  fill: var(--svg-color--662113, #662113);
  d: path("M28.043 35c.55 0 1-.45 1-1V2c0-.55-.45-1-1-1s-1 .45-1 1v32c0 .55.45 1 1 1");
}

.t1zb_55ua {
  fill: var(--svg-color--662113, #662113);
  d: path("M10 14.5h16V16H10z");
}

.tj1t-lp-v {
  fill: var(--svg-color--662113, #662113);
  d: path("M10 6.5h16V8H10zm0 24h16V32H10z");
}

.u9w1-9b5y {
  fill: var(--svg-color--bf6952, #bf6952);
  d: path("M26.043 35h2c.55 0 1-.45 1-1V2c0-.55-.45-1-1-1h-2c-.55 0-1 .45-1 1v32c0 .55.45 1 1 1");
}

.yhvpirhtx {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M8 35h2c.55 0 1-.45 1-1V2c0-.55-.45-1-1-1H8c-.55 0-1 .45-1 1v32c0 .55.45 1 1 1");
}

</style>
