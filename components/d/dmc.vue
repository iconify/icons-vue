<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="am9i73qts"/><path class="l06ti4b_d"/><path class="ac1badc2c"/><path class="jn611wbjh"/><path class="ozx3p3exx"/><path class="mc_1wxdpd"/><path class="dvvkspbxy"/><path class="pwop3eaog"/><path class="i7kp8672d"/><path class="pbwd0ab-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dmc" /></template>
<style>
.ac1badc2c {
  fill: var(--svg-color--001e1e, #001e1e);
  d: path("M4.912 4.424L3 19.594l3.375-9z");
}

.am9i73qts {
  fill: var(--svg-color--02828b, #02828b);
  d: path("m6.33 10.594l-1.4-6.188l3.729 6.188z");
}

.dvvkspbxy {
  fill: var(--svg-color--00504f, #00504f);
  d: path("M12 9.356s-2.138.765-3.212 1.136l3.211 5.18z");
}

.ft5dv1b6b {
  fill: none;
}

.i7kp8672d {
  fill: var(--svg-color--01a0a6, #01a0a6);
  d: path("m12 9.373l-3.212 1.136l3.211-5.175z");
}

.jn611wbjh {
  fill: var(--svg-color--02828b, #02828b);
  d: path("m17.67 10.594l1.4-6.188l-3.73 6.188z");
}

.l06ti4b_d {
  fill: var(--svg-color--00514f, #00514f);
  d: path("m6.33 10.594l-3.33 9l5.659-9z");
}

.mc_1wxdpd {
  fill: var(--svg-color--001e1e, #001e1e);
  d: path("M19.088 4.424L21 19.594l-3.375-9z");
}

.ozx3p3exx {
  fill: var(--svg-color--00514f, #00514f);
  d: path("m17.67 10.594l3.33 9l-5.66-9z");
}

.pbwd0ab-h {
  fill: var(--svg-color--028188, #028188);
  d: path("m12 9.373l3.218 1.125L12 5.334z");
}

.pwop3eaog {
  fill: var(--svg-color--001e1e, #001e1e);
  d: path("M12 9.349s2.15.77 3.218 1.142l-3.212 5.18V9.355z");
}

</style>
