<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="b_4z-lbwn"/><path class="maineimpp"/><path class="eugs9ub6n"/><path class="sovwtvf2x"/><path class="kolgdwbbj"/><path class="y9jq9t2wk"/><circle class="vkzsy3uyq"/><circle class="mw7uvpfka"/><path class="linsv_b-h"/><path class="yvmbsabao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:luggage" /></template>
<style>
.b_4z-lbwn {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M22 2h-8c-.55 0-1-.45-1-1s.45-1 1-1h8c.55 0 1 .45 1 1s-.45 1-1 1");
}

.eugs9ub6n {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M13 3h2v6h-2zm8 0h2v6h-2z");
}

.kolgdwbbj {
  fill: var(--svg-color--4289c1, #4289c1);
  d: path("M27 33H9c-1.1 0-2-.9-2-2V10c0-1.1.9-2 2-2h18c1.1 0 2 .9 2 2v21c0 1.1-.9 2-2 2");
}

.linsv_b-h {
  fill: var(--svg-color--2a6797, #2a6797);
  d: path("M25.5 12h-15c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h15c.275 0 .5.225.5.5s-.225.5-.5.5m0 9h-15c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h15c.275 0 .5.225.5.5s-.225.5-.5.5");
}

.maineimpp {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M13 1h2v2h-2zm8 0h2v2h-2z");
}

.mw7uvpfka {
  cx: 27px;
  cy: 35px;
  r: 1px;
  fill: var(--svg-color--292f33, #292f33);
}

.sovwtvf2x {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M7 25c-.55 0-1-.45-1-1v-6c0-.55.45-1 1-1s1 .45 1 1v6c0 .55-.45 1-1 1m3 9.2H9c-.55 0-1-.45-1-1v-1c0-.55.45-1 1-1h1c.55 0 1 .45 1 1v1c0 .55-.45 1-1 1m17 0h-1c-.55 0-1-.45-1-1v-1c0-.55.45-1 1-1h1c.55 0 1 .45 1 1v1c0 .55-.45 1-1 1");
}

.vkzsy3uyq {
  cx: 9px;
  cy: 35px;
  r: 1px;
  fill: var(--svg-color--292f33, #292f33);
}

.y9jq9t2wk {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M26 18H10c-.55 0-1-.45-1-1v-6c0-.55.45-1 1-1h16c.55 0 1 .45 1 1v6c0 .55-.45 1-1 1m0 13H10c-.55 0-1-.45-1-1V20c0-.55.45-1 1-1h16c.55 0 1 .45 1 1v10c0 .55-.45 1-1 1");
}

.yvmbsabao {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M11.5 12h-1c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h1c.275 0 .5.225.5.5s-.225.5-.5.5m0 9h-1c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h1c.275 0 .5.225.5.5s-.225.5-.5.5");
}

</style>
